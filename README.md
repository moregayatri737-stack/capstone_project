Library Management System

A full-stack Library Management System built using React, Node.js, Express, and MongoDB with JWT authentication and role-based access (Admin & User).

🚀 Features
🔐 Authentication

User & Admin Login

JWT-based authentication

Role-based access control

👤 User Module

View all available books

Request books

View request status (Pending / Issued)

See issued date

🛠 Admin Module

Add and delete books

View all user book requests

Issue books to users

Track issued books and users

🗂 Project Folder Structure
Library_Management_System/
├── backend/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── server.js
│   └── .env
│
├── frontend/
│   ├── src/
│   │   ├── pages/
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── index.html
│   └── package.json
│
├── .gitignore
└── README.md

▶️ How to Run the Project
1️⃣ Backend
cd backend
npm install
npm start


Create .env file:

MONGO_URI=mongodb://127.0.0.1:27017/library_management
JWT_SECRET=your_secret_key


Backend runs on:

http://localhost:5000

2️⃣ Frontend
cd frontend
npm install
npm run dev


Frontend runs on:

http://localhost:5173

🔑 Roles

Admin → Manage books, view & issue requests

User → Request books and view status

🛠 Tech Stack

Frontend: React (Vite)

Backend: Node.js, Express

Database: MongoDB

Authentication: JWT
