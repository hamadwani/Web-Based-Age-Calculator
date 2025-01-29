# Web-Based-Age-Calculator

Author- HAMAD WANI

Overview of the Web-Based Age Calculator

The project is a web-based Age Calculator that allows users to calculate their age based on their date of birth. The tool takes a user's birthdate as input and calculates their age in years, months, and days. This project involves using HTML for the structure, CSS for styling the interface, and JavaScript for handling the logic behind the age calculation. It provides a simple yet effective way for users to interact with the webpage and receive real-time feedback. The project is a great way to practice combining basic web development skills and creating a user-friendly experience.



1: HTML Structure: We begin with the HTML structure. We start by defining the document type and setting up the basic elements in the <head>, including linking an external CSS file. Inside the <body>, we create a div container that holds the calculator. It includes a <h1> heading, an input field for the date, a button to trigger the calculation, and a <p> tag to display the result.



2: JavaScript Functionality: The JavaScript handles the age calculation when the user clicks 'CALCULATE'. We first reference the input field and result element using document.getElementById. The input field’s maximum date is set to today, preventing future date selection.

When the button is clicked, the calculateAge() function runs. It checks whether the user has selected a date. If not, an error message is displayed. If a date is chosen, two Date objects are created: one for the user’s birthdate and one for the current date.

The script extracts the day, month, and year from both dates, and then calculates the difference in years, months, and days. It adjusts for cases where the current month or day is earlier than the birthdate’s month or day.

Finally, the calculated age is displayed on the page in years, months, and days, with the age values highlighted in yellow.



3: CSS Styling: Next, we style the page using CSS. The .container class spans the full page with a gradient background. Inside the calculator, we centre the calculator with a fixed width. The input box uses Flexbox to align the input field and button, while the button has a bright yellow background for a clear call-to-action. We also style the date picker and result display for better readability and visual appeal.
