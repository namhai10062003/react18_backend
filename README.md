# 🚀 React18 Backend

![Node.js](https://img.shields.io/badge/Node.js-v18.x-green?logo=node.js)
![Express.js](https://img.shields.io/badge/Express.js-v4.x-blue?logo=express)
![MongoDB](https://img.shields.io/badge/MongoDB-v6.x-brightgreen?logo=mongodb)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Build](https://img.shields.io/badge/Build-Passing-success)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

---

## 🧩 Overview

This repository contains the **backend API server** for the **React18 project**.  
It is built with **Node.js**, **Express.js**, and **MongoDB**, following the **MVC architecture** for clean, scalable, and maintainable code.

---

## 🛠 Technology Stack

| Technology | Description |
|-------------|-------------|
| **Node.js** | JavaScript runtime for backend development |
| **Express.js** | Web framework for building RESTful APIs |
| **MongoDB + Mongoose** | NoSQL database for document storage |
| **JWT Authentication** | Secure authentication with JSON Web Tokens |
| **Multer** | File upload handling (images, documents, etc.) |
| **Winston** | Logging and error tracking |
| **Jest** | Unit and integration testing |

---

## 📁 Folder Structure

| Folder | Description |
|---------|--------------|
| `src/config/` | Configuration files (DB connection, env setup) |
| `src/controllers/` | Handle incoming requests and responses |
| `src/middlewares/` | Custom middleware (auth, error handling, validation) |
| `src/models/` | Mongoose schema and data models |
| `src/routes/` | Define API endpoints and routes |
| `src/services/` | Core business logic and helper functions |
| `src/utils/` | General-purpose utilities |
| `src/app.js` | Main Express server entry point |
| `uploads/` | File upload storage |

###  Clone Repository

1️⃣ Clone Repository
```bash
git clone https://github.com/namhai10062003/react18_backend.git
cd react18_backend
2️⃣ Install Dependencies
npm install

PORT=3000
MONGODB_URI=mongodb://localhost:27017/react18_backend
JWT_SECRET=your_jwt_secret

⚠️ Lưu ý:
Khi bạn làm backend khác, hãy nhớ đổi lại đường dẫn MongoDB trong file .env
MONGODB_URI=mongodb://localhost:27017/my_new_backend

Production Mode 
npm start 
