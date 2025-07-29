# Course Selling Backend App

This is a Node.js backend for a Course Selling Platform. It handles user/admin authentication, course management, and course purchasing. The project is built using **Express.js**, **MongoDB**, **JWT**, and **bcrypt**.

---

## 📁 Folder Structure

course-selling/
├── middleware/          # Contains authentication and other middleware
├── node_modules/        # Project dependencies
├── routes/              # Route handlers for users, admins, and courses
├── .env                 # Environment-specific variables (not committed)
├── .env.example         # Sample environment config
├── .gitignore           # Files/folders to ignore in Git
├── config.js            # Configuration and constants
├── db.js                # MongoDB connection logic
├── index.js             # Application entry point
├── package.json         # Project metadata and scripts
└── package-lock.json    # Exact versions of installed packages



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
