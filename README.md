# Invinity - E-Invoicing Appliation

Invinity is a robust invoicing web application  designed to streamline financial workflows for freelancers and small businesses. By bridging the gap between complex accounting software and manual spreadsheets, Invinity offers a user-centric platform to manage the entire billing lifecycle.

## Technology stack
Invinity was developed using VS Code for streamlined coding and GitHub for secure, version-controlled repository management. During the engineering of the back-end, Postman was essential for debugging and testing RESTful API endpoints, ensuring seamless data flow between the client and server.

Based on the three-layer architecture chosen for the invoice application, the stack used is MERN,  pre-built technology stack based on JavaScript technologies. This stack was chosen because it makes the deployment of full-stack web applications easier and faster.

### Presentation Layer(Front-end)
Developed using React and Vite, focusing on a highly responsive UI/UX. Styling is handled via Tailwind CSS, featuring a custom purple-themed aesthetic designed for clarity and professional appeal.
### Application Layer(Back-end)
Powered by Node.js and Express.js, this layer manages the core business logic, including JWT-based authentication, server-side PDF generation, financial calculations and graphs.
### Data Layer(Database)
Utilizes MongoDB and Mongoose to provide a flexible, schema-based NoSQL storage solution for managing complex entity relationships (Clients, Vendors, Invoices and Reports).


## Visual Overview
### Authentication
The first page the user is brought to is the login page. If the user doesn’t have an account, they can navigate to the registration form using the “Register here” button at the bottom of the form. 
<p align="center">
  <img src="images/authentication.PNG" alt="Invinity Authentication" width="800">
  <br>
  <b>Figure 1:</b> <i>Secure Log In and Registration forms for Invinity users.</i>
</p>

### Navbar
The navbar contains the logo for Invinity and the four main pages: Dashboard, the default landing page after logging in, Invoice, Report and Database. Additionally, there is a Log Out button, which redirects the user to the login page.

### Dashboard
The dashboard of Invinity presents a personalized, small breakdown of invoicing activities. On the left side of the dashboard, users can view a breakdown of the current month’s financial status, including total number of invoices created during the current month, total collected, total oustanding and total overdue. On the right side of the dashboard, a line chart displays the totals for the entire year. 
At the bottom of the page, there is a breakdown of the entities in the user’s database, categorized by type.

<p align="center">
  <img src="images/dashboard.PNG" alt="Dashboard" width="800">
  <br>
  <b>Figure 1:</b> <i>Secure Log In and Registration forms for Invinity users.</i>
</p>
