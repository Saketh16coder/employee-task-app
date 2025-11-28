### ProU Employee & Task Management – Full Stack Application

A complete full-stack solution built for the ProU Technology Recruitment Assessment.

## This system demonstrates:

Secure portal login + signup pages

Internal employees & tasks dashboard

React + Tailwind frontend

Node.js/Express backend

SQLite persistent database

Custom client-side routing

Clean UI identical to ProU’s official theme

### 🧩 Tech Stack
## 🌐 Frontend

React (UMD)

Tailwind CSS (CDN)

Custom Router (history API)

Modular Components:

AuthForm

Dashboard

EmployeeForm

TaskForm

## 🖥 Backend

Node.js

Express.js

SQLite3

## REST APIs for:

Users

Employees

Tasks

### 📌 Key Features
✔ Login / Signup pages
✔ Dashboard with Employees + Tasks
✔ Add, edit, delete employees
✔ Add, edit, delete tasks
✔ Assign task to employee
✔ SQLite persistent database
✔ Full ProU-style UI
✔ Protected routes (/dashboard)
✔ Automatic redirect if logged out
✔ Logout button

### 🗂️ Project Structure
employee-task-app/
│
├── backend/
│   ├── db.js
│   ├── database.sqlite
│   ├── server.js
│   ├── package.json
│   
│
├── frontend/
│   ├── index.html
│   ├── app.js
│   ├── AuthForm.js
│   ├── Dashboard.js
│   ├── EmployeeForm.js
│   ├── TaskForm.js
│ 
│
└── README.md

### 🚀 How to Run the Full Stack App
## 1️⃣ Install backend dependencies
```
cd backend
npm install
```
## 2️⃣ Start backend server
``` npm run dev ```

## 3️⃣ Visit the frontend
```
http://localhost:4000/login
http://localhost:4000/signup
http://localhost:4000/dashboard
```

## 🔀 Routing Overview
Route	Purpose
/login	Login page
/signup	Registration page
/dashboard	Protected dashboard
*	All fallback to React router

### 📸 Screenshots

Add your screenshots here

## 🔹 Login Page

(image)

## 🔹 Signup Page

(image)

## 🔹 Dashboard (Employees + Tasks)

(image)

## 🔹 SQLite Tables

(image)

### Note:
✔ UI inspired by ProU official site
✔ Modern, responsive UX
✔ Full CRUD + authentication
