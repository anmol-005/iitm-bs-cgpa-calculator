CGPA Calculator
A web-based CGPA (Cumulative Grade Point Average) calculator designed for students to easily calculate their CGPA based on their courses and grades. The application is built with HTML, JavaScript, and it provides two intuitive ways to input academic data.

Live Demo
You can access the live, deployed version of the calculator here:

https://iitm-bs-cgpa-calculator-amber.vercel.app/

Features
Accurate CGPA Calculation: Calculates the CGPA based on the standard formula: Σ(Creditsᵢ * GradePointᵢ) / Σ(Creditsᵢ).

Two Input Modes: Users can choose their preferred method for entering data:

Input by Course: A comprehensive list of all available courses is displayed. Users can select the courses they have completed and then assign a grade to each.

Input by Grade: The interface displays sections for each possible grade (S, A, B, etc.). Users can then add courses directly into the relevant grade category.

Synchronized Views: The "Input by Course" and "Input by Grade" tabs are fully synchronized. Any changes made in one view will be instantly reflected in the other, ensuring data consistency.

Responsive Design: The layout is fully responsive and works seamlessly on desktops, tablets, and mobile devices.

User-Friendly Interface: A clean and modern UI built with Tailwind CSS makes the calculator easy and pleasant to use.

Dynamic Updates: The interface updates in real-time as you select courses and assign grades.

How to Use
Visit the live application at the link above. (Alternatively, you can open the index.html file locally in your web browser).

Choose your preferred input method:

For "Input by Course":

In the "Select Your Courses" section, check the box next to each course you have taken.

The selected courses will appear in the "Enter Your Grades" section below.

For each course, use the dropdown menu to select the grade you received.

For "Input by Grade":

Click on the "Input by Grade" tab.

You will see a section for each grade (S, A, B, etc.).

Use the "Add a course..." dropdown in each section to add the courses for which you received that specific grade.

You can remove a course from a grade section by clicking the '×' button.

Calculate: Once you have entered all your courses and grades, click the "Calculate CGPA" button.

View Result: Your final CGPA will be displayed at the bottom, along with a summary of the total points and credits used in the calculation.

Technical Stack
HTML: For the basic structure of the application.

Tailwind CSS: For styling and creating a responsive user interface.

JavaScript (Vanilla): For all the logic, including state management, DOM manipulation, and CGPA calculation.

Course Data
The list of courses and their corresponding credit values are hardcoded into the script tag within the cgpa_calculator.html file. This data is based on the provided curriculum information for the Data Science program.
