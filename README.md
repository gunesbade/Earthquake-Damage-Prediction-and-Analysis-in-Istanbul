# Earthquake Damage Prediction and Analysis in Istanbul

This website was developed as part of a **capstone project** to present neighborhood-based earthquake damage predictions in Istanbul. The system simulates potential impact in the case of a **7.5 Mw magnitude earthquake**, dynamically displaying prediction results based on user input using **JSP**, **MySQL**, **JDBC**, **HTTP**, and **CSS** technologies.

## Features

- Users select a district and neighborhood via dropdown menus
- Damage score, confidence value, and damage class are retrieved dynamically
- A graphical summary of damage classes in the selected district is displayed
- Runs locally and connects to a MySQL database using JDBC

## Technologies Used

- Java Server Pages (JSP)
- MySQL Database
- JDBC (Java Database Connectivity)
- HTML, CSS
- HTTP Servlet

## Website Pages

### ▪ Home Page
- Introductory text about the website
- Navigation bar linking to About and Contact pages
- District and neighborhood dropdown menus
- After selection and submission, user is directed to the results page

### ▪ Results Page
- Displays:
  - Predicted damage score
  - Confidence value
  - Damage class
  - Graph for the selected district
- “Go back” button returns the user to the home page

### ▪ About Page
- Describes the general structure and goal of the project
- Includes result graphs to inform the user
- Navigation to Home and Contact pages

### ▪ Contact Page
- Lists names and email addresses of project team members and advisor
- Navigation to Home and About pages

## Database Info

The `final_results` table in MySQL includes:
- `district`
- `neighborhood`
- `predicted_damage`
- `confidence`
- `damage_class_regression`

Queries are performed based on district and neighborhood input by the user.

---

*This system currently runs locally and has not been deployed publicly.*
