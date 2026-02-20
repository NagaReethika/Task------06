# Task------06
📌 Contact Form with JavaScript Validation
📖 Project Description

This project is a simple Contact Form built using HTML, CSS, and JavaScript.
It demonstrates client-side form validation for Name, Email, and Message fields.

The form also features a modern animated gradient background for a visually appealing UI.

🎯 Objective

Build a contact form with HTML

Validate inputs using JavaScript

Show error messages dynamically

Prevent form submission if inputs are invalid

Display a success message on valid submission

Use Regex for email validation

Apply animated CSS gradient background

🛠 Tools Used

VS Code – Code Editor

Chrome Browser – Testing and Debugging

HTML – Form structure

CSS – Styling and background animation

JavaScript – Input validation and dynamic messages

🧱 Features Implemented
✅ Form Fields

Name

Email

Message

Submit Button

✅ Validation

Fields cannot be empty

Email must be in valid format

Error messages displayed below inputs

Form submission prevented if invalid

Success message shown on valid submission

✅ UI Enhancements

Centered form layout

Styled input fields and buttons

Animated gradient background using CSS @keyframes

📂 Project Structure
ContactForm/
│
├── index.html       # Main HTML file with CSS and JS
└── README.md        # Project documentation
📜 Email Validation Regex
/^[^ ]+@[^ ]+\.[a-z]{2,3}$/

Ensures proper email format

Allows domain extensions of 2–3 characters

🧪 Test Cases
Test Case	Expected Result
Empty fields	Show error messages
Invalid email (abc@)	Show email error
Spaces only	Show error
Valid inputs	Show success message
🎨 CSS Background Animation
@keyframes gradientBG {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
}

Creates smooth, looping gradient background animation

🎓 Learning Outcomes

DOM Manipulation with JS

Event Handling (submit event)

Form Validation Techniques

Regular Expressions (Regex)

Preventing default form submission

Dynamic error and success messages

CSS animations for UI enhancement

🚀 Future Improvements

Real-time validation as user types

Responsive design for mobile devices

Dark mode toggle

Integration with backend server for actual form submission

👩‍💻 Author

Reethika Raavi
