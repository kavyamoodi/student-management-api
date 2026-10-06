# 🎓 Student Management API

### RESTful Student Management System using Spring Boot & MySQL

Student Management API is a backend application built with **Java, Spring Boot, and MySQL** to manage student records through a set of RESTful APIs.

The project demonstrates core backend development concepts including **CRUD operations, REST API design, database integration, JPA/Hibernate, and API testing**.

---

## 🚀 Key Features

* ➕ **Create Students** — Add new student records through a REST API.
* 📋 **Retrieve Students** — Fetch all student records from the database.
* ✏️ **Update Students** — Modify existing student information using the student ID.
* 🗑️ **Delete Students** — Remove student records by ID.
* 🗄️ **Database Integration** — Persists student data using MySQL.
* 📦 **Sample Data Initialization** — Automatically loads sample student records when the application starts.

---

## 🛠️ Tech Stack

| Category    | Technologies             |
| ----------- | ------------------------ |
| Language    | Java                     |
| Framework   | Spring Boot              |
| Database    | MySQL                    |
| ORM         | Hibernate / JPA          |
| API         | REST APIs                |
| API Testing | Postman / Thunder Client |
| Build Tool  | Maven                    |
| IDE         | IntelliJ IDEA            |

---

## 🔗 API Endpoints

| Method   | Endpoint             | Description           |
| -------- | -------------------- | --------------------- |
| `GET`    | `/api/students`      | Retrieve all students |
| `POST`   | `/api/students`      | Add a new student     |
| `PUT`    | `/api/students/{id}` | Update a student      |
| `DELETE` | `/api/students/{id}` | Delete a student      |

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
```

This structure demonstrates the typical flow of a **Spring Boot REST application** from API request to database operation.

---

## 🧪 Sample Data

The application uses `CommandLineRunner` to automatically insert **16 sample student records** when the application starts.

This makes it easier to test the API endpoints without manually entering initial data.

---

## 🖥️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/kavyamoodi/student-management-api.git
cd student-management-api
```

### 2. Configure MySQL

Create a MySQL database and configure the database connection details in the application's configuration file.

Example:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/student_db
spring.datasource.username=your_username
spring.datasource.password=your_password
```

### 3. Build the Project

```bash
mvn clean install
```

### 4. Run the Application

```bash
mvn spring-boot:run
```

The API will then be available locally for testing.

---

## 🧪 Testing the API

The endpoints can be tested using tools such as:

* **Postman**
* **Thunder Client**

Example:

```http
GET http://localhost:8080/api/students
```

---

## 📌 Project Highlights

* Designed and implemented a **RESTful backend API**.
* Implemented complete **CRUD functionality**.
* Integrated **Spring Boot with MySQL**.
* Used **JPA/Hibernate** for database persistence.
* Implemented automatic sample-data initialization.
* Tested REST endpoints using API testing tools.
* Followed a structured backend architecture for handling API requests and database operations.

---

## 🎯 What I Learned

This project strengthened my understanding of:

* Spring Boot application development
* REST API design
* CRUD operations
* JPA and Hibernate
* MySQL database integration
* Backend request/response handling
* API testing and debugging
* Maven-based Java projects

---

## 📂 Repository

[**View Source Code →**](https://github.com/kavyamoodi/student-management-api)

---

## 👩‍💻 About the Developer

**Kavya Moodi**
Computer Science & Engineering Student | Full-Stack Developer

Interested in building practical applications across **full-stack development, backend engineering, AI-powered systems, and cloud technologies**.

[GitHub →](https://github.com/kavyamoodi)
