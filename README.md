 Project Overview
This project is a scalable web application that allows users to:

Register & Login securely

Access a protected dashboard

Perform CRUD operations on data

Manage their profile

It follows modern full‑stack architecture with clear frontend‑backend separation.

 Tech Stack
Frontend
React.js

Material UI

Axios

React Router

Backend
Node.js

Express.js

MongoDB

JWT Authentication

Bcrypt Password Hashing

 Authentication & Security
User passwords encrypted using bcrypt

JWT tokens for session management

Protected routes for dashboard

API authentication middleware

 Dashboard Features
View logged‑in user profile

Create, Read, Update & Delete records

Search and filter data

Secure logout

🔗 API Features
User Registration

User Login

Token‑based Authentication

Profile Fetch & Update

CRUD APIs for data management

📂 Project Structure
primetrade-frontend-task/
│
├── frontend/     → React UI
├── backend/      → Express APIs
└── README.md

⚙️ How to Run Locally
1 Backend
cd backend
npm install
npm start
2 Frontend
cd frontend
npm install
npm start
Frontend: http://localhost:3000
Backend: http://localhost:2000

 Sample Test User
You can create a new user using the Register page and login.

 Deployment Ready
The project is structured to be easily deployed on:

Frontend: Vercel / Netlify

Backend: Render / Railway

Database: MongoDB Atlas

 Scalability Plan
Backend uses modular routes & controllers

JWT‑based stateless authentication

Frontend uses reusable components

Easy to integrate microservices in future

