# 🧮 CGPA Calculator

A web-based CGPA (Cumulative Grade Point Average) calculator designed for students to easily calculate their CGPA based on their courses and grades. The application is built with vanilla HTML, Tailwind CSS, and JavaScript, and it provides two intuitive ways to input academic data.

---

## 🚀 Live Demo

You can access the live, deployed version of the calculator here:

[**https://iitm-bs-cgpa-calculator-amber.vercel.app/**](https://iitm-bs-cgpa-calculator-amber.vercel.app/)

---

## ✨ Features

* **📊 Accurate CGPA Calculation:** Calculates the CGPA based on the standard formula:
    ```
    Σ(Creditsᵢ * GradePointᵢ) / Σ(Creditsᵢ)
    ```
* **↔️ Two Input Modes:** Users can choose their preferred method for entering data:
    1.  **Input by Course:** A comprehensive list of all available courses is displayed. Users can select the courses they have completed and then assign a grade to each.
    2.  **Input by Grade:** The interface displays sections for each possible grade (S, A, B, etc.). Users can then add courses directly into the relevant grade category.
* **🔄 Synchronized Views:** The "Input by Course" and "Input by Grade" tabs are fully synchronized. Any changes made in one view will be instantly reflected in the other, ensuring data consistency.
* **📱 Responsive Design:** The layout is fully responsive and works seamlessly on desktops, tablets, and mobile devices.
* **🎨 User-Friendly Interface:** A clean and modern UI built with Tailwind CSS makes the calculator easy and pleasant to use.
* **⚙️ Dynamic Updates:** The interface updates in real-time as you select courses and assign grades.

---

## 📖 How to Use

1.  **Visit the live application** at the link above.
2.  **Choose your preferred input method:**
    * **For "Input by Course":**
        1.  In the "Select Your Courses" section, check the box next to each course you have taken.
        2.  The selected courses will appear in the "Enter Your Grades" section below.
        3.  For each course, use the dropdown menu to select the grade you received.
    * **For "Input by Grade":**
        1.  Click on the "Input by Grade" tab.
        2.  You will see a section for each grade (S, A, B, etc.).
        3.  Use the "Add a course..." dropdown in each section to add the courses for which you received that specific grade.
        4.  You can remove a course from a grade section by clicking the '×' button.
3.  **Calculate:** Once you have entered all your courses and grades, click the **"Calculate CGPA"** button.
4.  **View Result:** Your final CGPA will be displayed at the bottom.

---

## 🛠️ Technical Stack

* **HTML:** For the basic structure of the application.
* **Tailwind CSS:** For styling and creating a responsive user interface.
* **JavaScript (Vanilla):** For all the logic, including state management, DOM manipulation, and CGPA calculation.

---
