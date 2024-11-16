# Creating a Portfolio Platform using Node.js

## Project Overview
This project aims to create a Portfolio Platform using Node.js, Express.js, and MongoDB for backend functionalities, EJS for frontend rendering, and various APIs for data visualization. The platform will allow users to register, login, view portfolio items, add new portfolio items, view data visualizations, and receive notifications via email using Nodemailer.

## Authentication and Authorization
### User Registration
- Users can sign up by providing a username, password, first name, last name, age, country, and gender.
- Passwords are hashed using bcrypt before storing in the database.
- Username uniqueness is enforced.

### User Login
- Users can log in using their username and password.
- Hashed passwords are compared during login authentication.

### Authorization
- User roles such as 'admin' or 'regular user' are defined and stored in the database.
- Authorization checks are implemented for routes requiring specific permissions.

## REST API
- Admins can add, edit, and delete portfolio items.
- Each portfolio item includes three pictures, two names for localization, two descriptions for localization, and timestamps for creation, update, and deletion.
- Portfolio items are displayed on the main page with a carousel showcasing the three pictures, name, and description.

## APIs
- Three different APIs are utilized to create visually appealing charts or graphs on three different pages.
- The visualizations provide interactivity and informative insights for better user engagement and understanding of the data.

## Sending Messages with Nodemailer
- Welcome messages are sent after user registration.
- Notifications are implemented for certain actions on the website.

### Responsive Design and User Interface
- EJS is used for frontend rendering to enhance the user interface with thoughtful design elements.
- The application is visually appealing and responsive.  


Tangbike Kural, BDA-2306

