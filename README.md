# MERN Task Management Tool

A full-stack task management application built with the **MERN stack** (MongoDB, Express.js, React.js, Node.js). This app enables users to register, log in, and manage their tasks effectively — including creating, updating, deleting, and marking tasks as completed.

---

## ✨ Features

- User authentication (sign up, log in, and log out)
- Task management (create, read, update, delete)
- JWT-based authentication for secure access
- User-specific task visibility
- RESTful API with Express.js
- MongoDB for persistent storage
- Responsive UI using React.js and Redux Toolkit

---

## 🛠 Tech Stack

**Frontend:**
- React.js
- Redux Toolkit
- React Router

**Backend:**
- Node.js
- Express.js

**Database:**
- MongoDB (with Mongoose for data modeling)

**Authentication:**
- JSON Web Tokens (JWT)

---

## 🚀 Installation Guide

### 🔧 Prerequisites

Make sure the following are installed on your system:

- [Node.js](https://nodejs.org/) (v12 or later)
- [MongoDB](https://www.mongodb.com/) (local installation or [MongoDB Atlas](https://www.mongodb.com/cloud/atlas))

---

### 📦 Clone the Repository

```bash
git clone https://github.com/Akrishna4/MERN-task-management-tool.git
cd MERN-task-management-tool
````

---

### 🔙 Backend Setup

1. Navigate to the backend directory:

```bash
cd backend
```

2. Install dependencies:

```bash
npm install
```

3. Create a `.env` file in the `backend` folder and add the following:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

4. Start the backend server:

```bash
npm run dev
```

> The backend will be running on: `http://localhost:5000`

---

### 🎨 Frontend Setup

1. Navigate to the frontend directory:

```bash
cd ../frontend
```

2. Install dependencies:

```bash
npm install
```

3. Start the frontend development server:

```bash
npm start
```

> The frontend will be running on: `http://localhost:3000`

---

## 📱 Usage

1. **Register or Log In:** Create a new account or log in to an existing one.
2. **Manage Tasks:** Add new tasks, edit or delete existing ones, and mark them as completed or pending.
3. **Protected Routes:** All task operations are secured with JWT authentication.

---

## 📁 Folder Structure

```
MERN-task-management-tool/
├── backend/
│   ├── config/        # DB and server configuration
│   ├── controllers/   # Logic for API routes
│   ├── models/        # Mongoose schemas
│   ├── routes/        # Express route definitions
│   ├── middleware/    # Auth middleware, error handling
│   └── server.js      # Entry point of backend server
│
├── frontend/
│   └── src/
│       ├── components/  # Reusable UI components
│       ├── redux/       # Redux state slices
│       ├── pages/       # Page components (Login, Home, etc.)
│       └── App.js       # Root component
│
├── .gitignore
├── package.json
├── README.md
```

---

## 🤝 Contributing

We welcome contributions!

```bash
1. Fork the repository
2. Create a new branch: git checkout -b feature/your-feature
3. Commit your changes: git commit -am 'Add feature'
4. Push the branch: git push origin feature/your-feature
5. Open a Pull Request 🎉
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 📬 Contact

If you have any questions, feel free to [open an issue](https://github.com/Akrishna4/MERN-task-management-tool/issues) or submit a pull request.

```


