# 🏦 Home Loan Finance Backend

This is the backend API for the Home Loan Finance Management System built with Spring Boot. It provides RESTful services for managing loan applications, customer profiles, disbursements, sanction letters, document verification, and user authentication.

---

## 🔗 Repository

- 🔗 Frontend Repo: [Loan Management System Frontend](https://github.com/sakshiathare/Home_Loan_Frontend)  
- 🔗 Backend Repo: [Home Loan Finance Backend](https://github.com/sakshiathare/home_loan_backend)

---

## 🚀 Features

- 🛡️ User Authentication & Role-based Authorization  
- 🏦 Loan Application Management (Apply, View, Update Status)  
- 📄 Document Upload and Verification  
- 💰 Disbursement Management & History  
- 📋 Sanction Letter Generation and Viewing  
- 📊 Credit Evaluation and Loan Stage History Tracking  

---

## 🧑‍💻 Technologies Used

- Java 17+ / Spring Boot  
- Spring Security (JWT)  
- Hibernate / JPA  
- Maven  
- MySQL  
- RESTful APIs  

---

## 📂 Project Structure (Backend)
Home_loan_Finance/
├── mvnw # Maven wrapper script for Linux/Mac
├── mvnw.cmd # Maven wrapper script for Windows
├── pom.xml # Maven project descriptor
├── src/
│ ├── main/
│ │ ├── java/
│ │ │ └── com/sit/homeloan/
│ │ │ ├── HomeLoanFinanceApplication.java # Main Spring Boot application
│ │ │ ├── config/ # Configuration classes
│ │ │ │ ├── SecurityConfig.java # JWT & security configuration
│ │ │ │ └── WebConfig.java # Web MVC & CORS configuration
│ │ │ ├── controller/ # REST API controllers
│ │ │ │ ├── AuthController.java # Login/Register endpoints
│ │ │ │ ├── LoanController.java # Loan-related endpoints
│ │ │ │ ├── DocumentController.java # Document upload & verification endpoints
│ │ │ │ └── UserController.java # User management endpoints
│ │ │ ├── dto/ # Data Transfer Objects
│ │ │ │ ├── LoanDTO.java
│ │ │ │ ├── UserDTO.java
│ │ │ │ └── AuthDTO.java
│ │ │ ├── enums/ # Enum classes
│ │ │ │ ├── Role.java
│ │ │ │ └── LoanStatus.java
│ │ │ ├── model/ # JPA Entity classes
│ │ │ │ ├── User.java
│ │ │ │ ├── LoanApplication.java
│ │ │ │ ├── Document.java
│ │ │ │ └── Disbursement.java
│ │ │ ├── repository/ # Spring Data JPA repositories
│ │ │ │ ├── UserRepository.java
│ │ │ │ ├── LoanRepository.java
│ │ │ │ ├── DocumentRepository.java
│ │ │ │ └── DisbursementRepository.java
│ │ │ ├── service/ # Service interfaces
│ │ │ │ ├── UserService.java
│ │ │ │ ├── LoanService.java
│ │ │ │ ├── DocumentService.java
│ │ │ │ └── DisbursementService.java
│ │ │ └── serviceimpl/ # Service implementations
│ │ │ ├── UserServiceImpl.java
│ │ │ ├── LoanServiceImpl.java
│ │ │ ├── DocumentServiceImpl.java
│ │ │ └── DisbursementServiceImpl.java
│ │ └── resources/
│ │ ├── application.properties # Application configuration
│ │ └── static/ # Optional static resources
│ └── test/ # Unit and integration tests
└── .mvn/
└── wrapper/
└── maven-wrapper.properties # Maven wrapper configuration

## 🔧 Setup Instructions

### ✅ Prerequisites

- Java JDK 17 or above  
- Maven 3.6+  
- MySQL Server running  
- IDE (IntelliJ, Eclipse, VS Code) recommended  

