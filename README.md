# 🏦 Java Banking Web Application

A full-stack **Java Banking Web Application** built using **Spring MVC**, **JDBC/JPA**, and **JSP**, designed to simulate real-world banking operations such as customer management, fund transfers, loan processing, OTP verification, and admin dashboards.

---

## 🚀 Features

### 👨‍💼 Admin Module
- Secure admin login
- Create and manage customers
- View customer transactions
- Loan approval & management
- Reports and dashboards

### 👤 Customer Module
- Secure login with OTP verification
- View account dashboard
- Fund transfer between accounts
- Loan application and status tracking
- Transaction statements
- Password reset via email

---

## 🛠️ Tech Stack

- **Backend:** Java, Spring MVC
- **Frontend:** JSP, HTML, CSS
- **Database:** MySQL
- **ORM / Persistence:** JPA / Hibernate
- **Build Tool:** Maven
- **Server:** Apache Tomcat
- **Email Service:** JavaMail (OTP & notifications)

---

## 📂 Project Folder Structure
---
---
src/main/java/com/bank
├── config → Application and MVC configuration
├── controller → Web controllers (Admin & Customer)
├── entity → JPA entity classes
├── repository → Data access layer
├── service → Business logic layer
└── util → Utility helpers

src/main/webapp
├── index.jsp
└── WEB-INF
├── web.xml
└── views → JSP pages

----

---



---

## Architecture

- **Controller Layer:** Handles HTTP requests and navigation  
- **Service Layer:** Contains business logic  
- **Repository Layer:** Database interaction using JPA  
- **View Layer:** JSP-based UI rendering  

---

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/Alexander1326/Java_Banking_Project.git

---
Import the project as a Maven project in Eclipse or IntelliJ.

Configure MySQL database and update credentials in configuration files.

Deploy the project on Apache Tomcat.

Access the application:

http://localhost:8080/Java_Banking_Project
Future Enhancements

Migration to Spring Boot

RESTful API integration

Modern frontend (React / Angular)

JWT-based authentication

Dockerized deployment
