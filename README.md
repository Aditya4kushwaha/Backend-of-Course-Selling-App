# Course Selling Backend App

This is a Node.js backend for a Course Selling Platform. It handles user/admin authentication, course management, and course purchasing. The project is built using **Express.js**, **MongoDB**, **JWT**, and **bcrypt**.

---

## 📁 Folder Structure

course-selling/
├── middleware/ # Middleware for auth and more
├── node_modules/ # Node dependencies
├── routes/ # All route handlers
├── .env # Environment variables
├── .env.example # Sample .env file
├── .gitignore # Git ignore file
├── config.js # App configuration
├── db.js # MongoDB connection
├── index.js # Main entry point
├── package.json
└── package-lock.json


---

## 🚀 Features

- ✅ User and Admin Signup/Login (JWT)
- ✅ Admin can create/update courses
- ✅ User can view & purchase courses
- ✅ Authentication middleware
- ✅ MongoDB integration using Mongoose

---

## 🧠 Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose)
- **Authentication**: JWT, bcrypt
- 
---

## 🔧 Installation

```bash
git clone https://github.com/your-username/course-selling-backend.git
cd course-selling-backend
npm install
