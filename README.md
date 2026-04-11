# 🚀 BlogHub – Full Stack Blogging Platform

BlogHub is a full-stack blogging web application built using Java (JDK 21), Spring Boot, Spring Data JPA, JSP, and MySQL.

It provides a structured blogging system where:
- ✍️ Users can create, edit, and manage blog posts  
- 🗂️ Posts are organized by categories  
- 🔐 Role-based access (ADMIN / USER) controls actions  
- ⚡ REST APIs power dynamic content rendering  

---

## 🛠️ Tech Stack

### 🔹 Backend
- Java (JDK 21)
- Spring Boot
- Spring Data JPA (Hibernate)
- REST APIs
- MySQL

### 🔹 Frontend
- HTML5
- CSS3
- JavaScript

### 🔹 Tools & Utilities
- STS
- Git & GitHub
- Maven

---

## ✨ Features

### 👤 User Features
- Register & Login (Session-based)
- Create blog posts
- Edit and delete own posts
- View posts by category
- Pagination & sorting of posts

### 🛡️ Admin Features
- Manage all users
- Manage categories
- Delete inappropriate posts
- Full control over platform content

### 📝 Blog Management
- Create / Update / Delete posts
- Category-wise post organization
- Pagination and sorting support
- DTO-based validation for clean data handling

### ⚙️ Backend Architecture
- Layered architecture (Controller → Service → Repository)
- DTO pattern for validation and data transfer
- Global exception handling
- Structured API responses

---


## 📂 Project Structure

<img width="408" height="713" alt="image" src="https://github.com/user-attachments/assets/63516331-6a87-482c-b57d-178272532808" />


---

## 🗃️ Database Tables (Main)

- users
- posts
- categories

---

## 🚀 How To Run The Project

1. Clone the repository

```bash
git clone https://github.com/your-username/BlogHub.git

---

## 📨 Email Notifications

Integrated JavaMail API to send:
- Registration OTP
- Password reset OTP
- Application confirmation
- Application status updates
- Employer notification on new application

---

## 🗃️ Database Tables (Main)

- users
- jobs
- applications
- resume_analysis_logs

---

## 🚀 How To Run The Project

1. Clone the repository
   
git clone https://github.com/PhoolSagar/HireSense.git


3. Import into Eclipse as Existing Maven Project

4. Configure:
- Database connection in DBConnection.java
- Email credentials in MailConfig.java

4. Deploy on Apache Tomcat

5. Run in browser:

http://localhost:8080/HireSense

---

## 🌐 Host It (Docker)

This repository now includes a containerized deployment setup:
- `Dockerfile`
- `docker-compose.yml`
- `.env.example`

### 1. Configure environment variables

Create `.env` from `.env.example` and set real mail credentials:

```bash
HIRESENSE_MAIL_USERNAME=your_email@gmail.com
HIRESENSE_MAIL_PASSWORD=your_gmail_app_password
```

### 2. Run with Docker Compose

From project root (`HireSense/`):

```bash
docker compose --env-file .env up -d --build
```

### 3. Open the app

```text
http://localhost:8080/HireSense/login.jsp
```

### 4. Runtime configuration keys

The app reads these environment variables at startup:
- `HIRESENSE_DB_URL`
- `HIRESENSE_DB_USERNAME`
- `HIRESENSE_DB_PASSWORD`
- `HIRESENSE_MAIL_USERNAME`
- `HIRESENSE_MAIL_PASSWORD`
- `HIRESENSE_APP_NAME`

If not provided, it falls back to values in `WEB-INF/web.xml`.

---

## 🔒 Security Features

- Session-based authentication
- Role-based access (User / Employer)
- Input validation
- Secure email authentication

---

## 📌 Future Improvements

- Interview scheduling system
- Admin dashboard
- In-app notification system
- Resume update management
- Cloud deployment

---

## 👨‍💻 Developed By

**Phoolsagar Singh**  

B.Tech Computer Science Engineering  

---

## 📷 Screenshots

# Home page
<img width="2159" height="1224" alt="image" src="https://github.com/user-attachments/assets/a7ad4249-4ea1-443b-bd15-972a8695fd1b" />

---
# Login Page
<img width="1228" height="781" alt="Screenshot 2026-02-12 192917" src="https://github.com/user-attachments/assets/d949acd0-a75c-40eb-a779-66713717984a" />

---
# SignIn Page
<img width="768" height="695" alt="image" src="https://github.com/user-attachments/assets/feb5facc-87f1-477c-b323-af03c3df9348" />

---
# User Dashboard
<img width="2128" height="1216" alt="image" src="https://github.com/user-attachments/assets/27ddac03-4d0a-46b3-821e-1f2a054c6293" />

---
# Employer Dashboard
<img width="2133" height="1219" alt="image" src="https://github.com/user-attachments/assets/2f043cf2-4f51-4a7c-aea2-be6277460b1b" />
<img width="2136" height="1188" alt="image" src="https://github.com/user-attachments/assets/bf1e4197-59d4-4fcb-a670-7a2cc6a9128b" />

---
# Admin Dashboard
<img width="2127" height="1216" alt="image" src="https://github.com/user-attachments/assets/60208cd4-083a-4d05-a136-700365532159" />
<img width="2132" height="1222" alt="image" src="https://github.com/user-attachments/assets/d092812b-92a2-454c-8fef-02399be39fcd" />









---

## ⭐ If You Like This Project

Give it a star on GitHub ⭐
