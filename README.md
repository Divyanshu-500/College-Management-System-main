🎓 College Management System

A full-stack College Management System built using the MERN-style architecture (without React).
The system digitizes academic and administrative operations for colleges.



📌 Project Overview

This system allows:

👨‍🎓 Students to view attendance and results

👩‍🏫 Faculty to manage attendance & marks

🧑‍💼 Admin to control the entire system

It eliminates manual record-keeping and ensures secure data management.



🏗️ System Architecture:
Client (HTML/CSS/JS)
        ↓
Express Server (Node.js)
        ↓
MongoDB Database



🚀 Core Features:

🔐 Authentication-
Secure password hashing (bcrypt)
Role-based login system
Session/JWT based access control

👨‍🎓 Student Management-
Register student
Update student details
View attendance
View results

👩‍🏫 Faculty Management-
Add attendance
Upload marks
Manage subjects

🧑‍💼 Admin Dashboard-
Manage users
Assign courses
Delete records
View analytics


🛠️ Technology Stack
Frontend	           HTML, CSS, JavaScript
Backend	               Node.js, Express.js
Database	           MongoDB
Version Control	       Git & GitHub



⚙️ Setup Instructions
1️⃣ Clone Repository
git clone https://github.com/Divyanshu-500/College-Management-System-main.git


2️⃣ Backend Installation
cd backend
npm install


3️⃣ Configure Environment

Create .env file:
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

4️⃣ Run Application
npm start



🌐 API Endpoints
| Method | Endpoint           | Description      |
| ------ | ------------------ | ---------------- |
| POST   | /api/auth/register | Register user    |
| POST   | /api/auth/login    | Login user       |
| GET    | /api/students      | Get all students |
| POST   | /api/attendance    | Add attendance   |
| POST   | /api/marks         | Upload marks     |



🔐 Security Features

Password hashing using bcrypt
Protected routes using middleware
Environment variables for sensitive data
Role-based authorization



📊 Database Design (Example)
Student Schema
{
  name: String,
  email: String,
  rollNumber: String,
  course: String,
  attendance: Number,
  marks: Object
}



🚀 Deployment Guide:

Deploy Backend (Render / Railway)-
Push code to GitHub
Connect repository to Render
Add environment variables
Deploy

Deploy Frontend-
Use Netlify
OR GitHub Pages




📈 Future Improvements-
Payment gateway integration
Notification system
PDF report generation
Cloud image upload
Docker containerization




🤝 Contribution Guidelines-
Fork the repository
Create a feature branch
Commit changes
Push branch
Create Pull Request



📊 Project Status-
🟢 Active Development



🧠 What I Learned-
REST API development
MongoDB schema modeling
Authentication & security
Git workflow
Error handling & debugging



👨‍💻 Author
Divyanshu Maurya
GitHub: https://github.com/Divyanshu-500