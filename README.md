📋 Registration Form with Validation

This project is a simple user registration form built using HTML, CSS, and JavaScript. It validates user input on the client side before submission to ensure the data is correctly formatted.

✨ Features

->Input fields for First Name, Last Name, Email, and Password.

->Real-time validation of form fields using JavaScript.

->Validation includes:

->Names must contain only alphabets.

->Email must be in a valid format.

->Password must have at least 8 characters, with lowercase, uppercase, digit, and special character.

->Shows error messages for empty or invalid fields.

->Password visibility toggle button.

->On successful validation, redirects to a success page.

Clean, modern responsive design with a styled background.

📂 Project Structure
│── index.html         # Registration form HTML
│── style.css          # Styling for form and success page
│── index.js           # JavaScript for validation and interactions
│── success.html       # Success message page after submission
│── README.md          # Project documentation

🚀 How to Run This Project Locally
1.Download this repository to your local machine.
2.Open the index.html file in any modern browser.
3.Fill in the form fields and click Create Account.
4.If all validations pass, it will redirect you to the success page.
5.If there are errors, they will be shown next to the relevant inputs.

📖 How It Works

1.The JavaScript listens to user input and validates each field on every key press.
2.When you click the submit button:
  1.It checks if each field is filled.
  2.It tests the field content against specific regular expressions:
      1.Names only allow alphabets.
      2.Email should match standard email format.
      3.Password requires minimum length and complexity.
3.If any validation fails, it shows error messages and highlights the input box in red.
4.Password field has a toggle button to show/hide the password.
5.If all inputs are valid, the user is redirected to a success page confirming account creation.



MIT License © 2025 K.V.Kalavathi
