# 🎓 Student API - Spring Boot + MySQL Project

A simple REST API built using **Spring Boot** and **MySQL** to manage student records for CRUD operations.

---

## 🚀 Features

- ✅ Add a new student
- ✅ View all students
- ✅ Update student details
- ✅ Delete a student by ID
- ✅ Auto-inserts 16 sample records at startup

---

## 🛠️ Tech Stack

- Java
- Spring Boot
- MySQL
- Hibernate (JPA)
- Thunder Client / Postman (API Testing)
- IntelliJ IDEA

---

## 📂 Endpoints (Testable with Thunder Client / Postman)

| Method | Endpoint             | Description           |
|--------|----------------------|-----------------------|
| GET    | `/api/students`      | List all students     |
| POST   | `/api/students`      | Add a new student     |
| PUT    | `/api/students/{id}` | Update student        |
| DELETE | `/api/students/{id}` | Delete student by ID  |

---

## 🧪 Sample Data Inserted Automatically

## 🧪 Sample Data Inserted Automatically

Sample student records are automatically inserted using CommandLineRunner during application startup to simulate real-world data and test API performance.

## 🖥️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Kavy-git/student-management-api.git
