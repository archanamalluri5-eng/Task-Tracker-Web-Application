# Task Tracker Web Application

A full-stack Task Tracker Web Application built using the MERN Stack (MongoDB, Express.js, React.js, Node.js). This application allows users to create, view, update, and delete tasks with a responsive user interface and RESTful API integration.

## Features

- Create new tasks
- View all tasks
- Update existing tasks
- Delete tasks
- Form validation
- REST API integration
- MongoDB database
- Responsive design
- Dynamic updates without page refresh

## Tech Stack

### Frontend
- React.js
- Axios
- CSS3

### Backend
- Node.js
- Express.js

### Database
- MongoDB Atlas
- Mongoose

## Project Structure

```
task-tracker/
│
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── App.jsx
│   │   ├── App.css
│   │   └── main.jsx
│   ├── package.json
│   └── vite.config.js
│
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   ├── package.json
│   └── .env
│
└── README.md
```

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/task-tracker.git
```

### Backend Setup

```bash
cd server
npm install
npm run dev
```

### Frontend Setup

```bash
cd client
npm install
npm run dev
```

## Environment Variables

Create a `.env` file inside the **server** folder.

```env
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

## REST API Endpoints

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | /api/tasks | Get all tasks |
| POST | /api/tasks | Create task |
| PUT | /api/tasks/:id | Update task |
| DELETE | /api/tasks/:id | Delete task |

## Deployment

### Frontend
Deploy on **Vercel**

### Backend
Deploy on **Render**

### Database
MongoDB Atlas

## Future Enhancements

- User Authentication
- Task Categories
- Search and Filter
- Due Date Notifications
- Dark Mode
- Priority Levels




# Screenshots

## Dashboard
Application title: Task Tracker
Task list displayed
Add Task button
Search bar
Filter (All, Pending, Completed)
<img width="1600" height="1188" alt="image" src="https://github.com/user-attachments/assets/442388ee-a693-45b4-b668-560d05282498" />

## Add Task
Title input
Description textarea
Status dropdown
Due Date picker
Save button
<img width="1024" height="682" alt="image" src="https://github.com/user-attachments/assets/811d93af-3381-4bb9-909e-b6862327dadd" />


## Edit Task
Existing task details pre-filled
Update button
Cancel button
<img width="1440" height="757" alt="image" src="https://github.com/user-attachments/assets/5d99ee2b-e60e-4e86-a3e0-cbbd73eb9171" />

## Mobile View
Task cards stacked vertically
Mobile-friendly buttons
Responsive navigation

<img width="800" height="957" alt="image" src="https://github.com/user-attachments/assets/59cdc730-08f9-4b50-8cbc-91908d88e156" />

## Author

Archana Malluri

## License

This project is developed for educational and internship evaluation purposes.
