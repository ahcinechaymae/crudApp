# 🗂️ Task Manager App — Full Stack CRUD Application

A modern task management app built using **Spring Boot** for the backend and **React + Vite** for the frontend. It features a RESTful API, task creation/editing forms, confirmation popups before deletion, and a clean, responsive user interface.

---

## 📁 Project Structure

crud-app/
├── backend/ # Java Spring Boot (REST API + MySQL)
├── frontend/
├── README.md
└── .gitignore


---

## 🚀 Features

### 🔧 Backend (Spring Boot)
- Fully RESTful API built with Spring Boot
- MySQL integration using Spring Data JPA & Hibernate
- Entity: `Task` with validation using `@NotBlank`
- Endpoints: GET, POST, PUT, DELETE
- Spring Security configured to allow public access during development
- Proper error handling using `ResponseEntity`

### 🎨 Frontend (React + Vite)
- Functional components using **React Hooks**
- Routing with **React Router** (List page + Task form page)
- Fetches data from backend using the `fetch` API (no Axios)
- Task form with add/edit functionality
- Task list with **Edit** / **Delete** options
- Confirmation modal before deletion
- Styled with clean modern **CSS** (or Tailwind CSS optionally)

---

## ⚙️ Installation Guide

### 🔹 Prerequisites

- [Node.js](https://nodejs.org/)
- [Java 17+](https://adoptium.net/)
- [MySQL Server](https://www.mysql.com/)
- [Maven](https://maven.apache.org/)
- Git

---

### 🖥️ Run the project locally

#### 1. Clone the repository

```bash
git clone https://github.com/your-username/crud-app.git
cd crud-app


2. Run the backend (Spring Boot)

cd backend
# Make sure to configure your DB in src/main/resources/application.properties
# Example:
# spring.datasource.url=jdbc:mysql://localhost:3306/crudapp
# spring.datasource.username=root
# spring.datasource.password=yourpassword

mvn spring-boot:run

3. Run the frontend (React + Vite)
cd ../frontend
npm install
npm run dev

The app will be running at http://localhost:3000

🧪 Testing

Frontend: Jest + React Testing Library

| Layer    | Technologies                        |
| -------- | ----------------------------------- |
| Frontend | React, Vite, React Router, CSS      |
| Backend  | Spring Boot, Spring Data JPA, MySQL |
| Tools    | Maven, GitHub, IntelliJ, VS Code    |

📸 Screenshots
![image](https://github.com/user-attachments/assets/daafe9b4-48c2-4359-87fe-20bff1964ee4)
![image](https://github.com/user-attachments/assets/85b6c39e-8aa0-42ce-9b4a-16f5918df8be)



👩‍💻 Author
Developed by Chaymaa Ahcine
💼 Software Engineer

