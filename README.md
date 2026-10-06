# 🎓 Student Management API

### RESTful Student Management System using Spring Boot & MySQL

Student Management API is a backend application built using **Java, Spring Boot, and MySQL** to manage student records through RESTful APIs.

The project demonstrates core backend development concepts including **REST API design, CRUD operations, database integration, JPA/Hibernate, and API testing**.

---

## 🚀 Key Features

- ➕ **Create Students** — Add new student records through a REST API.
- 📋 **Retrieve Students** — Fetch all student records from the database.
- ✏️ **Update Students** — Modify existing student information using the student ID.
- 🗑️ **Delete Students** — Remove student records by ID.
- 🗄️ **MySQL Integration** — Store and manage student data using a relational database.
- 📦 **Sample Data Initialization** — Automatically inserts sample student records when the application starts.

---

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| Language | Java |
| Framework | Spring Boot |
| Database | MySQL |
| ORM | Hibernate / JPA |
| API | REST APIs |
| API Testing | Postman / Thunder Client |
| Build Tool | Maven |
| IDE | IntelliJ IDEA |

---

## 🔗 API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| `GET` | `/api/students` | Retrieve all students |
| `POST` | `/api/students` | Add a new student |
| `PUT` | `/api/students/{id}` | Update a student |
| `DELETE` | `/api/students/{id}` | Delete a student |

---

## 🏗️ Application Flow

```text
API Client
(Postman / Thunder Client)
        ↓
REST Controller
        ↓
Service Layer
        ↓
JPA Repository
        ↓
Hibernate / JPA
        ↓
MySQL Database
