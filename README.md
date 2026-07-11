# Travlr Full-Stack Web Application

Travlr is a full-stack travel website developed as part of a Full Stack Development course. The application uses Node.js and Express for server-side functionality and Handlebars for rendering dynamic views.

The project demonstrates foundational full-stack development concepts, including backend routing, middleware, server-side templating, static asset management, error handling, and organized application structure.

## Features

* Node.js and Express server configuration
* Server-side rendering with Handlebars
* Modular route handling
* Middleware integration
* Static HTML, CSS, JavaScript, and image serving
* Custom 404 and server error handling
* Organized routes, views, and public asset directories
* Responsive travel website interface

## Technologies Used

* Node.js
* Express.js
* JavaScript
* Handlebars
* HTML
* CSS
* Morgan
* Cookie Parser
* Git
* GitHub

## Project Structure

```text
TravelSite-MERN/
├── app.js
├── package.json
├── package-lock.json
├── bin/
│   └── www
├── public/
│   ├── images/
│   ├── javascripts/
│   └── stylesheets/
├── routes/
│   ├── index.js
│   └── users.js
├── views/
│   ├── error.hbs
│   ├── index.hbs
│   └── layout.hbs
└── README.md
```

## Installation

### Prerequisites

Before running the project, make sure the following software is installed:

* Node.js
* npm
* Git

### Clone the Repository

```bash
git clone https://github.com/dself-dev/TravelSite-MERN.git
```

Move into the project directory:

```bash
cd TravelSite-MERN
```

### Install Dependencies

```bash
npm install
```

## Running the Application

Start the application with:

```bash
npm start
```

Open a browser and navigate to:

```text
http://localhost:3000
```

## Available Routes

| Route    | Description                         |
| -------- | ----------------------------------- |
| `/`      | Displays the main travel website    |
| `/users` | Returns a basic user route response |

## What I Learned

Through this project, I gained practical experience with:

* Creating and configuring a Node.js application
* Building a web server with Express.js
* Creating and managing application routes
* Using middleware to process HTTP requests
* Rendering server-side views with Handlebars
* Serving static assets through Express
* Structuring a full-stack application into logical directories
* Handling 404 and server-side application errors
* Managing dependencies with npm
* Using Git and GitHub for version control

## Future Improvements

This project currently demonstrates the foundational structure of a full-stack Node.js and Express application. Planned improvements include:

* Connecting the application to a database such as MongoDB
* Replacing static travel package information with dynamic database content
* Adding full create, read, update, and delete functionality
* Creating administrative tools for managing travel packages
* Adding user registration, login, and authentication
* Implementing authorization for users and administrators
* Creating RESTful API endpoints
* Adding form validation and improved error handling
* Improving mobile responsiveness and accessibility
* Adding automated testing
* Containerizing the application with Docker
* Deploying the application to a cloud platform
* Expanding the frontend with a modern JavaScript framework

## Academic Context

This application was developed as part of a Full Stack Development course. The purpose of the project was to apply server-side development concepts in a working application and demonstrate an understanding of routing, templating, middleware, error handling, and full-stack project organization.

## Author

**Dennis Selfinger**

* Email: [dselfinger.dev@gmail.com](mailto:dselfinger.dev@gmail.com)
* GitHub: [dself-dev](https://github.com/dself-dev)
* Portfolio: [dself-dev.github.io/2026_portfolio_website](https://dself-dev.github.io/2026_portfolio_website/)
