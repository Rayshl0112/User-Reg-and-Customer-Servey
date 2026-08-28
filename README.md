User Registration and Customer Experience Survey

Project Description

This project is a simple web-based User Registration and Customer Experience Survey System created using HTML, CSS, and JavaScript.

The project contains two main pages:

User Registration – Allows users to create an account by entering a username and password. It includes real-time password requirement validation and password confirmation.

Customer Experience Survey – Allows users to provide personal information, rate their overall satisfaction, select features they used, and submit detailed feedback.

The project focuses on creating functional, organized, and user-friendly web forms with client-side validation and interactive elements.

Features

User Registration

Username input

Password input

Confirm password input

Real-time password requirement checking

Password requirements:

At least one lowercase letter

At least one uppercase letter

At least one number

Minimum of 8 characters

Password confirmation validation

Registration success message

Link to the customer survey

Customer Experience Survey

Full name input

Email address input

Phone number input

Overall satisfaction rating

Feature selection using checkboxes

"How did you hear about us?" dropdown

Date of service input

Frequency of use input

Suggestions/feedback text area

Send Feedback button

Clear Form button

Home button

Thank-you message

Technologies Used

HTML5 – Structure and form elements

CSS3 – Layout, styling, colors, gradients, buttons, and form design

JavaScript – Password validation, form interaction, and dynamic content

Google/Segoe UI-style typography – Used for the overall visual appearance

Project Structure

Palisoc-MariaRaychelle_#LE3/
│
├── register.html
├── survey.html
├── style.css
│
├── code/
│   ├── register.txt
│   ├── survey.txt
│   └── style.txt
│
└── video/
    └── Palisoc-MariaRaychelle_video_#LE3.mp4

File Description

File

Description

register.html

Main registration page containing the registration form and JavaScript validation

survey.html

Customer experience survey page

style.css

Shared stylesheet used by both HTML pages

code/register.txt

Copy of the registration HTML source code

code/survey.txt

Copy of the survey HTML source code

code/style.txt

Copy of the CSS source code

video/Palisoc-MariaRaychelle_video_#LE3.mp4

Project demonstration video

How to Run

No server or database is required because this project uses client-side HTML, CSS, and JavaScript.

Option 1: Open Directly

Extract the project folder.

Open the Palisoc-MariaRaychelle_#LE3 folder.

Double-click register.html.

The registration page will open in your web browser.

Option 2: Using Visual Studio Code

Open the project folder in Visual Studio Code.

Open register.html.

Run the file using a browser or the Live Server extension.

Test the registration and survey forms.

How to Use

Registration Page

Enter a username.

Enter a password.

When the password field is selected, the password requirements will appear.

Enter a password that satisfies all requirements.

Enter the same password in the confirmation field.

Click Register.

If the passwords match, the registration form is cleared and the survey link is displayed.

Click Go to Survey to proceed to the survey.

Survey Page

Enter your personal information.

Select an overall satisfaction rating.

Select the features you used.

Choose how you heard about the service.

Enter the date of service and frequency of use if applicable.

Add suggestions or feedback.

Click Send Feedback to submit the form.

Use Clear Form to reset the survey.

Use Home to return to the registration page.

Validation

The registration form uses JavaScript to check the password while the user types.

The password is checked for:

[a-z]  → lowercase letter
[A-Z]  → uppercase letter
\d     → number
8+      → minimum length

The form also checks whether the password and confirm password fields contain the same value.

Notes

This project is a front-end demonstration.

The forms currently do not store information in a database.

The method="POST" attribute is present in the forms, but no backend processing script is included.

User information entered into the forms is therefore not permanently saved.

The project can be extended in the future by adding a backend such as PHP and a database such as MySQL.

Author

Maria Raychelle Palisoc

Laboratory Exercise #3 – Web Development

