# ✨ Rapid Web App Builder

🌐 Live: 🔗 https://task-6qrl.onrender.com

This is a **Full Stack MERN application** built as part of a Rapid Web App Builder challenge. It helps developers build full-featured web applications **quickly**, with modern best practices and features like authentication, image uploads, dashboards, form validation, dark mode, and more.

---

## 📌 Project Objective

The goal of this project is to provide a **production-ready boilerplate** for building scalable and responsive MERN stack applications with:

- User registration & login
- Real-time dashboard display of user data
- File/image upload to the cloud (Cloudinary)
- Protected routes with JWT
- Frontend + backend input validation
- Dark mode switch
- Redux state management

---

## 🛠️ Tech Stack

### 🔹 Frontend

- **React.js** – Frontend library for building user interfaces
- **Redux** – Global state management
- **Tailwind CSS** – Utility-first CSS framework for styling
- **Formik & Yup** – For form state management and validation
- **React Router DOM** – Client-side routing

### 🔹 Backend

- **Node.js** – JavaScript runtime for backend
- **Express.js** – Web server framework
- **MongoDB & Mongoose** – Database and ODM
- **Multer** – Middleware for handling file uploads
- **Cloudinary SDK** – Image hosting and transformation
- **JWT** – For secure authentication
- **bcryptjs** – For password encryption

---

## 🎯 Features Explained

|         Feature            |                               Description                                        |
|--------------------------- |----------------------------------------------------------------------------------|
| ✅ User Authentication    | Sign up, login with hashed passwords, token-based sessions using JWT              |
| 🧾 Form Validation        | Prevents invalid data entry using Formik, Yup (frontend) and middleware (backend) |
| 🖼️ Image Upload           | Users can upload profile pictures using Multer → stored in Cloudinary             |
| 🌗 Dark Mode Toggle       | Users can switch between light and dark themes with saved preference              |
| 🧑‍💻 Dashboard              | Displays user data entered during sign-up/login in a protected route              |
| 📱 Responsive UI          | Layout adjusts for mobile, tablet, and desktop devices                            |

---


✅ Use Case Example

When a user signs up:

- Their data is validated (both client & server side)
- Password is hashed and stored in MongoDB
- JWT is issued and stored in localStorage
- User is redirected to the dashboard
- Uploaded profile picture goes to Cloudinary
- The dashboard fetches the user’s info and displays it



🌒 Dark Mode

Dark mode toggle is built using React state and Tailwind classes. The choice can be stored in localStorage so users see the same theme when they return.


