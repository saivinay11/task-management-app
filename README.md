# Task Management App

## Project Overview
This project is a Task Management application that allows users to create, manage, and track their tasks efficiently. The application provides an intuitive interface and helps users stay organized by keeping all their tasks in one place.

## Tech Stack
- **Frontend:** React, Redux, Bootstrap
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)
- **Deployment:** Heroku

## Features
- User authentication with sign up and login functionality
- Create, read, update, and delete tasks
- Mark tasks as completed
- Filter tasks by status (completed, pending)
- Responsive design for mobile and desktop

## Setup Instructions
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/saivinay11/task-management-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd task-management-app
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```
5. Open your browser and go to `http://localhost:3000` to view the app.

## API Documentation
The backend of the application provides a RESTful API for CRUD operations on tasks. Here’s a brief overview:
- `POST /api/tasks` - Create a new task
- `GET /api/tasks` - Retrieve all tasks
- `GET /api/tasks/:id` - Retrieve a specific task by ID
- `PUT /api/tasks/:id` - Update a task by ID
- `DELETE /api/tasks/:id` - Delete a task by ID

## Architecture
The architecture follows the MVC (Model-View-Controller) pattern where:
- **Model**: Represents the data and business logic. In this app, we use MongoDB to store task data.
- **View**: The user interface, built with React.
- **Controller**: Manages the flow of data between the model and view, implemented with Express on the server side.

---

## Updated on: 2026-04-20 09:10:41 UTC