# 📌 Grievance Management System

## 📖 Overview

The **Grievance Management System** is a full-stack web application designed to manage complaints and grievances efficiently within an organization or institution.

The system allows users to submit grievances while administrators can review, manage, and resolve them through a centralized dashboard.

This project demonstrates the implementation of a **modern full-stack architecture using React and Spring Boot**.

---

# 🚀 Features

### 👤 User Features

* Register and login
* Submit grievances or complaints
* View submitted complaints
* Track grievance status

### 🛠️ Admin Features

* Admin login
* View all grievances
* Update grievance status
* Manage users and complaints

---

# 🧑‍💻 Tech Stack

### Frontend

* React
* Vite
* JavaScript
* CSS

### Backend

* Spring Boot
* Java
* REST APIs

### Database

* MySQL

---

# 📂 Project Structure

```
Grievance-Management-System
│
├── backend                 # Spring Boot Application
│   ├── src
│   ├── pom.xml
│
├── frontend                # React + Vite Application
│   ├── src
│   ├── package.json
│   ├── vite.config.js
│
└── README.md
```

---

# ⚙️ How to Run the Project

## 1️⃣ Run Backend (Spring Boot)

Navigate to backend folder:

```
cd backend
```

Run the Spring Boot application:

```
mvn spring-boot:run
```

Backend will start on:

```
http://localhost:8080
```

---

## 2️⃣ Run Frontend (React + Vite)

Navigate to frontend folder:

```
cd frontend
```

Install dependencies:

```
npm install
```

Run the application:

```
npm run dev
```

Frontend will run on:

```
http://localhost:5173
```

---

# 🔗 API Communication

The React frontend communicates with the Spring Boot backend using REST APIs.

Example API endpoints:

```
GET /api/grievances
POST /api/grievances
PUT /api/grievances/{id}
DELETE /api/grievances/{id}
```

---

# 🎯 Project Objectives

* Provide a centralized grievance management system
* Improve transparency in complaint handling
* Allow users to track grievance status
* Enable administrators to manage complaints efficiently

---

# 🔮 Future Enhancements

* JWT Authentication & Authorization
* Email notification system
* File upload for grievance evidence
* Dashboard analytics
* Deployment on cloud

---

# 👨‍💻 Author

**Rohit Taksande**

GitHub:
https://github.com/Rohit2612-dev
