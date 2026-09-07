Student API in Express

A simple Student API project built with Node.js, Express.js, and EJS for CSC220 Web Development II.

This project demonstrates Express middleware, JSON body parsing, GET and POST routes, 404 handling, and server-side rendering with EJS.

Features

Logger middleware that displays the HTTP method, URL, and request time

JSON request body parsing with express.json()

View all students as JSON

View a student by ID

Filter students by major

Add a new student with a POST request

Handle invalid routes with a JSON 404 response

Render the student list as an HTML page using EJS

Technologies Used

JavaScript

Node.js

Express.js

EJS

JSON

Project Structure

student-api-express/
├── views/
│   └── students.ejs
├── .gitignore
├── app.js
├── package.json
├── package-lock.json
├── students.json
└── README.md

Installation

Clone or download the project, open the project folder in the terminal, and install the dependencies:

npm install
