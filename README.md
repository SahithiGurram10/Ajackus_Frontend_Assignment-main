# Ajackus Frontend Assignment – Employee Directory Web App

Objective
Develop a responsive and interactive Employee Directory Web Interface using HTML, CSS, JavaScript, and Freemarker templates. The goal is to assess your understanding of modern front-end development principles and your ability to build clean, modular, and user-friendly interfaces without relying heavily on external APIs.
Requirements
User Interface:
Dashboard Page
Display a list/grid of employees with the following details:
 Employee ID, First Name, Last Name, Email, Department, and Role.
Use a Freemarker template to render the list (mock data will be passed to the template).
Each employee card/row should have an "Edit" and "Delete" button.

<img width="686" height="279" alt="image" src="https://github.com/user-attachments/assets/2e2ba288-01b6-4b67-940b-7542894aad62" />


Add/Edit Form Page
Create a form (HTML) to add or edit an employee.
This form should be styled and validated using CSS and JavaScript.
Fields: First Name, Last Name, Email, Department, Role.
Use simple client-side JavaScript to handle form submission, validation, and updating the data locally (in memory, no backend required).

<img width="547" height="560" alt="image" src="https://github.com/user-attachments/assets/b0f3e8c4-2674-491e-87f4-5f82e3308252" />



Filter/Sort/Search
Add a filter popup or sidebar that allows filtering employees by:
First Name
Department
Role
Add a search bar at the top to search employees by name or email.
Add sorting capability by First Name and Department.

<img width="667" height="341" alt="image" src="https://github.com/user-attachments/assets/2a172523-1052-4560-a78b-76bd97024a12" />

Pagination or Infinite Scroll
Implement pagination (options for 10, 25, 50, 100) or infinite scrolling using JavaScript.


Responsive Design
Ensure the app is responsive and looks good on desktop, tablet, and mobile.


Functionality
Data Handling:
 Use a local JavaScript array to simulate employee data (can be loaded via <#assign> tag in Freemarker from a mock JSON object).
Form Validation:
 Validate fields like email format, required fields, etc., using JavaScript.
No Backend Interaction Required:
 You do not need to connect to any backend API or perform real network calls.


Error Handling & Validations:
Display validation errors clearly (e.g., invalid email, required fields).
If the user tries to delete an employee without selecting one or editing without saving, handle these interactions gracefully.


Guidelines:
Focus on writing clean HTML/CSS/JS.
Use vanilla JavaScript (optional: minimal use of libraries if really needed).
Use Freemarker where dynamic HTML rendering is required.
Try to modularize your CSS and JS.
Add comments in your code where necessary to explain logic.


Submission:
Upload your project to a public GitHub repo.
Include a README file with:
Setup and run instructions.
Overview of your project structure.
Screenshots (optional but recommended).
Reflection: Challenges faced and what you’d improve if given more time.
Timeline:
The faster turnaround will be awarded bonus points. 

Evaluation Criteria:
HTML/CSS code quality and responsiveness.
Use of JavaScript for DOM manipulation and interactivity.
Freemarker integration and clean templating.
User Experience (UX) & Interface Design (UI).
Code structure, readability, and validation handling.

