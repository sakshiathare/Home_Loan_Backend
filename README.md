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
 ├── mvnw                      # Maven wrapper script (Linux/Mac)
 ├── mvnw.cmd                  # Maven wrapper script (Windows)
 ├── pom.xml                   # Maven project descriptor file
 ├── src/
 │   ├── main/
 │   │   ├── java/
 │   │   │   └── com/
 │   │   │       └── sit/
 │   │   │           └── homeloan/
 │   │   │               ├── HomeLoanFinanceApplication.java      # Main Spring Boot application class
 │   │   │               ├── config/                             # Configuration classes (e.g., WebConfig, SecurityConfig)
 │   │   │               ├── controller/                         # REST Controller classes
 │   │   │               ├── dto/                                # Data Transfer Object classes
 │   │   │               ├── enums/                              # Enum classes (e.g., User roles, Loan status)
 │   │   │               ├── model/                              # JPA Entity classes (User, LoanApplication, etc.)
 │   │   │               ├── repository/                         # Spring Data JPA repository interfaces
 │   │   │               ├── service/                            # Service interfaces
 │   │   │               └── serviceimpl/                        # Service implementation classes
 │   │   └── resources/
 │   │       └── application.properties                          # Spring Boot application configuration file
 │   └── test/                                                    # Unit and integration tests
 └── .mvn/
     └── wrapper/
         └── maven-wrapper.properties                            # Maven wrapper properties file

---

## 🔧 Setup Instructions

### ✅ Prerequisites

- Java JDK 17 or above  
- Maven 3.6+  
- MySQL Server running  
- IDE (IntelliJ, Eclipse, VS Code) recommended  

