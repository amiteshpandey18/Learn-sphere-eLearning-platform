<h1 align="center">📘 Learn Sphere – E-Learning Platform</h1>

<p align="center">
  A full-stack e-learning web application built using <b>Spring Boot</b> and <b>Thymeleaf</b>.
</p>

<p align="center">
  Java • Spring Boot • JPA • MySQL • Thymeleaf • Bootstrap
</p>

---

## 📌 Project Description

Learn Sphere is a full-stack e-learning platform developed as a learning project using Spring Boot.  
The application allows trainers to create and manage courses and lessons, while students can enroll in courses, watch lessons, and add comments.

This project helped me understand real-world backend development concepts such as layered architecture, database integration, and frontend-backend communication.

---

## 🚀 Features

### 👨‍🏫 Trainer Module
- Trainer registration and login
- Create courses
- Add lessons to courses
- View created courses and lessons

### 🎓 Student Module
- Student registration and login
- View available courses
- Enroll in courses (purchase simulation)
- Access enrolled courses and lessons
- Watch lesson videos

### 💬 Comment System
- Students can add comments on lessons
- Comments are saved in the database
- AJAX is used for adding comments without page reload

---

## 🛠 Tech Stack

- **Backend:** Java, Spring Boot  
- **Frontend:** Thymeleaf, HTML, CSS, Bootstrap  
- **Database:** MySQL  
- **ORM:** Spring Data JPA (Hibernate)  
- **Others:** jQuery, AJAX  

---

## 🏗 Project Architecture

Client (Browser / UI)
        ↓
Thymeleaf Templates (HTML + CSS + Bootstrap)
        ↓
Controller Layer
        ↓
Service Layer (Interface)
        ↓
Service Layer (Implementation)
        ↓
Repository Layer (Spring Data JPA)
        ↓
MySQL Database

