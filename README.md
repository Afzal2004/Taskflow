# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

# 🚀 TaskFlow - Smart Task Manager

A modern Full Stack MERN Task Management Application that helps users organize, manage, and track their daily tasks efficiently.

## 🌟 Features

* 🔐 User Authentication (JWT)
* 👤 User Registration & Login
* ➕ Create New Tasks
* 📋 View All Tasks
* 🗑️ Delete Tasks
* 🔍 Search Tasks
* 📊 Dashboard Analytics
* 📈 Task Completion Progress
* 📱 Responsive Design
* 🎨 Modern UI/UX
* 🔒 Protected Routes
* ☁️ MongoDB Database Integration

---

## 🛠️ Tech Stack

### Frontend

* React.js
* React Router DOM
* Axios
* CSS3

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Authentication

* JWT (JSON Web Token)
* bcrypt.js

---

## 📂 Project Structure

```bash
TaskFlow/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/taskflow.git
```

### Backend Setup

```bash
cd backend
npm install
npm run dev
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

## 🔑 Environment Variables

Create a `.env` file inside the backend folder:

```env
PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key
```

---

## 🚀 Future Enhancements

* ✏️ Edit Task
* 🌙 Dark Mode
* 🎯 Task Priority Levels
* 📅 Due Dates
* 📊 Charts & Analytics
* 🔔 Notifications
* 👤 User Profile
* Drag & Drop Task Management

---


## ⭐ Support

If you like this project, give it a ⭐ on GitHub and share your feedback.
