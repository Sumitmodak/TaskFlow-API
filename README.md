# TaskFlow API

A secure and RESTful Task Management API built with **Node.js** and **Express.js**. This project provides backend services for the TaskFlow Lite application, supporting complete CRUD operations with proper validation, middleware, and standardized API responses.

## Features

* RESTful API design
* Create, Read, Update and Delete (CRUD) tasks
* Express.js backend
* In-memory data storage
* Input validation
* Centralized error handling
* CORS support
* Helmet security headers
* Morgan request logging
* Environment variable configuration
* Swagger API documentation
* Postman collection for API testing

## Tech Stack

* Node.js
* Express.js
* CORS
* Helmet
* Morgan
* UUID
* Dotenv
* Swagger UI

## Project Structure

```text
taskflow-api/
├── server.js
├── package.json
├── .env
├── src/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── models/
│   ├── data/
│   ├── utils/
│   └── docs/
└── tests/
```

## Installation

```bash
git clone <repository-url>
cd taskflow-api
npm install
```

## Environment Variables

Create a `.env` file in the project root.

```env
PORT=5000
NODE_ENV=development
```

## Run the Project

Development mode:

```bash
npm run dev
```

Production mode:

```bash
npm start
```

## API Endpoints

| Method | Endpoint         | Description             |
| ------ | ---------------- | ----------------------- |
| GET    | `/api/tasks`     | Get all tasks           |
| GET    | `/api/tasks/:id` | Get a task by ID        |
| POST   | `/api/tasks`     | Create a new task       |
| PUT    | `/api/tasks/:id` | Update an existing task |
| DELETE | `/api/tasks/:id` | Delete a task           |

## API Documentation

Swagger Documentation:

```
http://localhost:5000/api-docs
```

## Testing

Use the included Postman collection to test all endpoints.

Test coverage includes:

* Create Task
* Get All Tasks
* Get Task by ID
* Update Task
* Delete Task
* Validation Errors
* 404 Not Found
* 500 Internal Server Error

## Project Status

Completed as part of a Backend REST API assignment using Node.js and Express.


This project is developed for educational and learning purposes.
