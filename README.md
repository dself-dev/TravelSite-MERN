# Travlr Getaways – Full-Stack Travel Management Application

Travlr Getaways is a full-stack web application built with **Node.js**, **Express.js**, **MongoDB**, **Mongoose**, and **Handlebars**. The application demonstrates server-side web development, RESTful API design, database integration, and dynamic content rendering using the **Model-View-Controller (MVC)** architecture.

Travel package information is stored in MongoDB, retrieved through REST API endpoints, and dynamically rendered to users through reusable Handlebars templates.

---

## Features

- Full-stack web application built with Node.js and Express.js
- MongoDB database integration using Mongoose
- RESTful API for retrieving travel package information
- Dynamic server-side rendering with Handlebars
- MVC (Model-View-Controller) application architecture
- Express middleware for request logging, cookies, JSON parsing, and serving static assets
- Reusable Handlebars partials
- MongoDB database seeding from JSON data
- Modular routes, controllers, models, and views
- Custom 404 and server error handling

---

## Technologies Used

### Backend

- Node.js
- Express.js
- JavaScript
- REST APIs

### Database

- MongoDB
- Mongoose

### Frontend

- Handlebars
- HTML5
- CSS3
- JavaScript

### Development Tools

- Git
- GitHub
- npm
- Morgan
- Cookie Parser

---

## Architecture

The application follows the **Model-View-Controller (MVC)** design pattern.

```
Browser
   │
   ▼
Express Routes
   │
   ▼
Controllers
   │
   ▼
MongoDB (Mongoose)
   │
   ▼
Handlebars Views
```

This architecture separates routing, business logic, data access, and presentation, making the application easier to maintain, test, and extend.

---

## REST API

### Get All Trips

```
GET /api/trips
```

Returns all travel packages stored in MongoDB.

### Get Trip by Code

```
GET /api/trips/:tripCode
```

Returns a single travel package matching the supplied trip code.

---

## Project Structure

```
TravelSite-MERN/
│
├── app_api/
│   ├── controllers/
│   ├── models/
│   └── routes/
│
├── app_server/
│   ├── controllers/
│   ├── routes/
│   ├── views/
│   └── models/
│
├── data/
├── public/
├── bin/
├── app.js
├── package.json
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/dself-dev/TravelSite-MERN.git
```

Navigate into the project:

```bash
cd TravelSite-MERN
```

Install dependencies:

```bash
npm install
```

Start MongoDB.

Seed the database:

```bash
node app_api/models/seed.js
```

Run the application:

```bash
npm start
```

Open your browser:

```
http://localhost:3000
```

Travel page:

```
http://localhost:3000/travel
```

REST API:

```
http://localhost:3000/api/trips
```

---

## What I Learned

Through this project I gained experience with:

- Building a full-stack web application using Node.js and Express.js
- Designing and implementing RESTful APIs
- Connecting Express applications to MongoDB using Mongoose
- Creating Mongoose schemas and data models
- Organizing applications using the MVC architecture
- Building reusable server-side templates with Handlebars
- Working with asynchronous JavaScript and database queries
- Creating modular controllers and routes
- Implementing middleware in Express
- Seeding MongoDB databases from JSON data
- Returning structured JSON responses from API endpoints
- Using Git and GitHub for version control

---

## Future Improvements

Future enhancements planned for this project include:

- Adding an Angular frontend to transition the application into a **MEAN Stack** project
- Building full CRUD functionality for travel packages
- Implementing JWT authentication and role-based authorization
- Creating an administrative dashboard for managing travel packages
- Adding user registration and account management
- Implementing trip search, filtering, and sorting
- Improving mobile responsiveness and accessibility
- Containerizing the application with Docker
- Deploying the application to AWS
- Adding automated unit and integration testing
- Integrating a modern frontend framework while maintaining a scalable RESTful backend architecture

---

## Academic Context

This application was developed as part of a Full Stack Development course to demonstrate backend development, MongoDB integration, RESTful API design, server-side rendering, middleware, and software architecture principles.

---

## Author

**Dennis Selfinger**

Email: dselfinger.dev@gmail.com

GitHub: https://github.com/dself-dev

Portfolio: https://dself-dev.github.io/2026_portfolio_website/