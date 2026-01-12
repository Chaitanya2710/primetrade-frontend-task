📌 Project Overview
PrimeTrade is a web application built using the MERN stack that allows users to:

Register & Login

Perform CRUD (Create, Read, Update, Delete) operations

Store and manage data in MongoDB

Use a responsive and interactive frontend

This project demonstrates full‑stack development, API integration, authentication, and database management.

🛠️ Tech Stack
Frontend
React.js

Material UI

Axios

React Router

Backend
Node.js

Express.js

MongoDB

Mongoose

JWT Authentication

📁 Project Structure
primetrade-frontend-task/
│
├── frontend/          → React User Interface
│
├── backend/           → Express.js APIs
│   ├── models/        → MongoDB models
│   ├── routes/        → API routes
│   ├── controllers/  → API logic
│   └── server.js      → Backend entry point
│
├── .gitignore         → Git ignored files
├── README.md          → Project documentation


⚙️ Features
🔐 User Registration & Login

📄 CRUD APIs for data management

🔄 Frontend connected with backend APIs

🗄️ MongoDB database integration

📦 RESTful API architecture

🎨 Clean UI using Material UI

▶️ How to Run Locally
1️⃣ Start Backend
cd backend
npm install
npm start
Backend will run on:
👉 http://localhost:2000

2️⃣ Start Frontend
cd frontend
npm install
npm start
Frontend will run on:
👉 http://localhost:3000

🔗 API & Application Flow
React frontend sends requests to Express backend

Express APIs interact with MongoDB

Responses are sent back and displayed in UI

🌐 Future Improvements
Add role‑based authentication

Improve UI & dashboards

Add validations

Deploy to cloud (Vercel / Render / MongoDB Atlas)

