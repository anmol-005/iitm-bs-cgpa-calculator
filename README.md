<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CGPA Calculator README</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji";
            line-height: 1.6;
            color: #24292e;
            background-color: #ffffff;
            margin: 0;
            padding: 45px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            border: 1px solid #e1e4e8;
            border-radius: 6px;
        }
        h1, h2 {
            border-bottom: 1px solid #eaecef;
            padding-bottom: 0.3em;
            margin-top: 24px;
            margin-bottom: 16px;
            font-weight: 600;
        }
        h1 {
            font-size: 2em;
        }
        h2 {
            font-size: 1.5em;
        }
        a {
            color: #0366d6;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        code {
            font-family: "SFMono-Regular", Consolas, "Liberation Mono", Menlo, Courier, monospace;
            font-size: 85%;
            padding: 0.2em 0.4em;
            margin: 0;
            background-color: rgba(27,31,35,0.05);
            border-radius: 3px;
        }
        pre {
            padding: 16px;
            overflow: auto;
            font-size: 85%;
            line-height: 1.45;
            background-color: #f6f8fa;
            border-radius: 3px;
        }
        pre code {
            padding: 0;
            margin: 0;
            background-color: transparent;
            border: 0;
        }
        ul, ol {
            padding-left: 2em;
            margin-top: 0;
            margin-bottom: 16px;
        }
        li {
            margin-bottom: 0.25em;
        }
        blockquote {
            margin: 0 0 16px 0;
            padding: 0 1em;
            color: #6a737d;
            border-left: 0.25em solid #dfe2e5;
        }
        hr {
            height: .25em;
            padding: 0;
            margin: 24px 0;
            background-color: #e1e4e8;
            border: 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🧮 CGPA Calculator</h1>
        <p>A web-based CGPA (Cumulative Grade Point Average) calculator designed for students to easily calculate their CGPA based on their courses and grades. The application is built with vanilla HTML, Tailwind CSS, and JavaScript, and it provides two intuitive ways to input academic data.</p>
        
        <hr>

        <h2>🚀 Live Demo</h2>
        <p>You can access the live, deployed version of the calculator here:</p>
        <p><a href="https://iitm-bs-cgpa-calculator-amber.vercel.app/"><strong>https://iitm-bs-cgpa-calculator-amber.vercel.app/</strong></a></p>

        <hr>
        
        <h2>✨ Features</h2>
        <ul>
            <li><strong>📊 Accurate CGPA Calculation:</strong> Calculates the CGPA based on the standard formula:
                <pre><code>Σ(Creditsᵢ * GradePointᵢ) / Σ(Creditsᵢ)</code></pre>
            </li>
            <li><strong>↔️ Two Input Modes:</strong> Users can choose their preferred method for entering data:
                <ol>
                    <li><strong>Input by Course:</strong> A comprehensive list of all available courses is displayed. Users can select the courses they have completed and then assign a grade to each.</li>
                    <li><strong>Input by Grade:</strong> The interface displays sections for each possible grade (S, A, B, etc.). Users can then add courses directly into the relevant grade category.</li>
                </ol>
            </li>
            <li><strong>🔄 Synchronized Views:</strong> The "Input by Course" and "Input by Grade" tabs are fully synchronized. Any changes made in one view will be instantly reflected in the other, ensuring data consistency.</li>
            <li><strong>📱 Responsive Design:</strong> The layout is fully responsive and works seamlessly on desktops, tablets, and mobile devices.</li>
            <li><strong>🎨 User-Friendly Interface:</strong> A clean and modern UI built with Tailwind CSS makes the calculator easy and pleasant to use.</li>
            <li><strong>⚙️ Dynamic Updates:</strong> The interface updates in real-time as you select courses and assign grades.</li>
        </ul>

        <hr>

        <h2>📖 How to Use</h2>
        <ol>
            <li><strong>Visit the live application</strong> at the link above. (Alternatively, you can open the <code>cgpa_calculator.html</code> file locally in your web browser).</li>
            <li><strong>Choose your preferred input method:</strong>
                <ul>
                    <li><strong>For "Input by Course":</strong>
                        <ol>
                            <li>In the "Select Your Courses" section, check the box next to each course you have taken.</li>
                            <li>The selected courses will appear in the "Enter Your Grades" section below.</li>
                            <li>For each course, use the dropdown menu to select the grade you received.</li>
                        </ol>
                    </li>
                    <li><strong>For "Input by Grade":</strong>
                        <ol>
                            <li>Click on the "Input by Grade" tab.</li>
                            <li>You will see a section for each grade (S, A, B, etc.).</li>
                            <li>Use the "Add a course..." dropdown in each section to add the courses for which you received that specific grade.</li>
                            <li>You can remove a course from a grade section by clicking the '×' button.</li>
                        </ol>
                    </li>
                </ul>
            </li>
            <li><strong>Calculate:</strong> Once you have entered all your courses and grades, click the <strong>"Calculate CGPA"</strong> button.</li>
            <li><strong>View Result:</strong> Your final CGPA will be displayed at the bottom, along with a summary of the total points and credits used in the calculation.</li>
        </ol>

        <hr>

        <h2>🛠️ Technical Stack</h2>
        <ul>
            <li><strong>HTML:</strong> For the basic structure of the application.</li>
            <li><strong>Tailwind CSS:</strong> For styling and creating a responsive user interface.</li>
            <li><strong>JavaScript (Vanilla):</strong> For all the logic, including state management, DOM manipulation, and CGPA calculation.</li>
        </ul>
        
        <hr>

        <h2>📚 Course Data</h2>
        <blockquote>
            <p>The list of courses and their corresponding credit values are hardcoded into the <code>script</code> tag within the <code>cgpa_calculator.html</code> file. This data is based on the provided curriculum information for the Data Science program.</p>
        </blockquote>
    </div>
</body>
</html>
