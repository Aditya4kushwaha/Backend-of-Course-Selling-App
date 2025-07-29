# Course Selling Backend App

This is a Node.js backend for a Course Selling Platform. It handles user/admin authentication, course management, and course purchasing. The project is built using **Express.js**, **MongoDB**, **JWT**, and **bcrypt**.

---

## 📁 Folder Structure

course-selling/

├── middleware/          
├── node_modules/        
├── routes/             
├── .env                
├── .env.example         
├── .gitignore           
├── config.js            
├── db.js                
├── index.js            
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
  
---

## 🔧 Installation

```bash
git clone https://github.com/Aditya4kushwaha/Backend-of-Course-Selling-App.git
cd course-selling-backend
npm install
```
## 🛠️ Setup

Create a `.env` file in the root directory and add:

```env
PORT=3000
MONGO_URI=mongodb://localhost:27017/courseselling
JWT_SECRET=your_jwt_secret
```

## Run the backend server
```bash
npm start        # For production use
npm run dev      # Requires nodemon

