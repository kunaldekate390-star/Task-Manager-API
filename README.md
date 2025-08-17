# Task Manager API

This is a simple task manager API built with Node.js, Express, MongoDB, and JWT authentication. It allows users to manage their tasks with features for creating, retrieving, updating, and deleting tasks.

## Features

- User authentication using JWT
- CRUD operations for tasks
- MongoDB for data storage

## Technologies Used

- Node.js
- Express
- MongoDB (with Mongoose)
- JSON Web Tokens (JWT)
- dotenv for environment variables
- CORS for cross-origin requests

## Setup Instructions

1. Clone the repository:
   
   git clone <repository-url>
   

2. Navigate to the project directory:
   
   cd task-manager-api
   

3. Install the dependencies:
   
   npm install
   

4. Create a .env file in the root directory and add the following environment variables:
   
   PORT=5000
   MONGO_URI=<your-mongodb-uri>
   JWT_SECRET=<your-jwt-secret>
   

5. Start the application:
   
   npm start
   

## API Endpoints

### Authentication

- *POST /api/auth/login*: Log in a user and receive a JWT token.

### Task Management

- *POST /api/tasks*: Create a new task.
- *GET /api/tasks*: Retrieve all tasks.
- *GET /api/tasks/:id*: Retrieve a task by ID.
- *PUT /api/tasks/:id*: Update a task by ID.
- *DELETE /api/tasks/:id*: Delete a task by ID.

## Usage

After starting the server, you can use tools like Postman or curl to interact with the API endpoints. Make sure to include the JWT token in the Authorization header for protected routes.

## License

This project is licensed under the MIT License.
