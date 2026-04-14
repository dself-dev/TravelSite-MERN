## Author

**Dennis Selfinger**  
Email: dselfinger.dev@gmail.com  

Created for a Full Stack Development course.

And here is the full README with your info included:

# Travlr Project

This project was created for a Full Stack Development course. It is a Node.js and Express web application that uses Handlebars for server-side rendering. The project demonstrates the fundamentals of backend routing, templating, middleware, and application structure in a full stack environment.

## Purpose

The purpose of this project was to practice building and organizing a full stack web application using Express. It also shows how static website content can be integrated into a server-based application structure.

## Features

- Express server setup
- Handlebars view engine
- Route handling
- Static file serving
- Error handling for 404 and server errors
- Basic project organization using routes, views, and public assets

## Technologies Used

- Node.js
- Express
- Handlebars (`hbs`)
- Morgan
- Cookie Parser

## Project Structure

```text id="9v11qx"
travlr-project/
├── app.js
├── package.json
├── routes/
│   ├── index.js
│   └── users.js
├── views/
│   ├── index.hbs
│   ├── error.hbs
│   └── layout.hbs
├── public/
├── bin/
│   └── www
└── package-lock.json
How to Run the Project
Install dependencies:
npm install
Start the application:
npm start
Open the app in your browser at:
http://localhost:3000
Routes
/ — renders the main page
/users — returns a simple text response
What I Learned

Through this project, I practiced:

Setting up an Express application
Using middleware in Node.js
Creating and managing routes
Rendering views with Handlebars
Organizing a full stack project into logical folders
Handling errors in a web application
Academic Context

This application was developed as part of a Full Stack Development class project. The goal was to apply course concepts in a working web application and demonstrate understanding of server-side development patterns.

Future Improvements

If this project were expanded further, possible improvements could include:

Adding database integration
Creating dynamic travel package data
Building out full CRUD functionality
Improving the front-end styling and responsiveness
Adding authentication and user management
Author

Dennis Selfinger
Email: dselfinger.dev@gmail.com

Created for a Full Stack Development course.
