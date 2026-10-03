# MERN Stack To-Do List

## Project Description

This project is a full-stack To-Do List application developed using the MERN stack.

The application allows users to:

* Add new tasks
* View all tasks
* Mark tasks as completed or incomplete
* Delete tasks

## Technologies Used

### Frontend

* React.js
* Vite
* Axios
* HTML
* CSS

### Backend

* Node.js
* Express.js
* Mongoose
* REST API

### Database

* MongoDB Atlas

## Project Structure

```text
MERN-ToDoList/
├── backend/
│   ├── models/
│   │   └── Task.js
│   ├── routes/
│   │   └── taskRoutes.js
│   ├── .env
│   ├── server.js
│   ├── package.json
│   └── package-lock.json
│
├── frontend/
│   ├── src/
│   │   ├── App.jsx
│   │   ├── App.css
│   │   └── main.jsx
│   ├── package.json
│   └── package-lock.json
│
├── screenshots/
│   ├── 01-add-task.png
│   ├── 02-completed-task.png
│   └── 03-delete-task.png
│
└── README.md
```

## Database Schema

The Task model contains:

* `title` – String
* `completed` – Boolean, default false
* `createdAt` – Date, default current date/time

## REST API Endpoints

| Method | Endpoint         | Description     |
| ------ | ---------------- | --------------- |
| GET    | `/api/tasks`     | Fetch all tasks |
| POST   | `/api/tasks`     | Add a new task  |
| PUT    | `/api/tasks/:id` | Update a task   |
| DELETE | `/api/tasks/:id` | Delete a task   |

## How to Run

### Backend

Open a terminal:

```bash
cd backend
npm install
node server.js
```

Backend URL:

```text
http://localhost:5000
```

### Frontend

Open another terminal:

```bash
cd frontend
npm install
npm run dev
```

Frontend URL:

```text
http://localhost:5173
```

## Important

The `.env` file contains MongoDB credentials and should not be shared publicly.

The `node_modules` folders should not be included in the submission ZIP.

## Screenshots

The screenshots demonstrate:

1. Adding and displaying tasks
2. Completing a task
3. Deleting a task

## Conclusion

This project demonstrates CRUD operations using React, Node.js, Express.js, MongoDB, and Mongoose through REST APIs.
