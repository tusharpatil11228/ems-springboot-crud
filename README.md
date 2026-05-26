# ems-springboot-crud
Employee Management System using Spring Boot, Spring Data JPA, Thymeleaf and MySQL with full CRUD functionality.

---

## 📌 Project Overview

This project is a simple Employee Management System developed using Spring Boot.  
It allows users to perform CRUD (Create, Read, Update, Delete) operations on employee records.

The application follows the MVC (Model View Controller) architecture and uses MySQL database for storing employee information.

---

## 🚀 Features

- Add New Employee
- View Employee List
- Update Employee Details
- Delete Employee
- MySQL Database Integration
- Responsive Bootstrap UI
- Spring Boot MVC Architecture
- CRUD Operations using Spring Data JPA

---

## 🛠️ Technologies Used

- Java 17
- Spring Boot
- Spring MVC
- Spring Data JPA
- Thymeleaf
- MySQL
- Bootstrap 5
- HTML/CSS
- Maven
- Git & GitHub

---

## 📂 Project Structure

```text
src
 └── main
      ├── java
      │     └── com.project.ems
      │            ├── controller
      │            ├── entity
      │            ├── repository
      │            ├── service
      │            └── EmsApplication.java
      │
      └── resources
            ├── templates
            ├── static
            └── application.properties
```

---

## ⚙️ Database Configuration

Create MySQL database:

```sql
CREATE DATABASE ems_db;
```

Update `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/ems_db
spring.datasource.username=root
spring.datasource.password=tusharpatil@1704
```

---

## ▶️ How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/tusharpatil11228/ems-springboot-crud.git
```

2. Open project in IntelliJ IDEA

3. Configure MySQL database

4. Run `EmsApplication.java`

5. Open browser:

```text
http://localhost:8080
```

---

## 📸 Screenshots

Example:

- Home Page
- Add Employee Page
- Update Employee Page

---

## 📖 Learning Concepts Covered

- Spring Boot Basics
- MVC Architecture
- CRUD Operations
- Dependency Injection
- Thymeleaf Template Engine
- Database Connectivity
- JPA Repository
- Form Handling
- Bootstrap UI Integration

---

## 👨‍💻 Author

Tushar Patil

---

## ⭐ Future Improvements

- Employee Search Feature
- Pagination
- Login Authentication
- REST API Version
- Role-Based Access
- Docker Deployment
