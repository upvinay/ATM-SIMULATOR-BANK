# ATM-SIMULATOR-BANK
# 🏦 ATM Simulator with Bank Encryption

A secure desktop-based **ATM Simulator** developed using **Java Swing, JDBC, MySQL, and encryption techniques**.

The project simulates common ATM and banking operations while focusing on **secure authentication, encrypted sensitive information, database management, and transaction handling**.

---

## 📌 Project Overview

The ATM Simulator is a Java-based banking application designed to demonstrate how ATM and basic banking operations can be implemented using a graphical user interface and a relational database.

The system provides separate functionality for customers and administrators. It supports account management, ATM transactions, card-related operations, passbook management, and secure handling of sensitive banking information.

Security features are incorporated to protect sensitive information and reduce direct exposure of confidential data.

---

# 🚀 Features

## 👤 Customer / ATM Module

- Customer Login
- Secure Authentication
- PIN Verification
- Balance Inquiry
- Cash Withdrawal
- Cash Deposit
- Fast Cash
- Mini Statement
- Transaction History
- Account Information
- PIN Change
- Security Question / Answer
- Date of Birth Verification
- Passbook Management
- Card Management

---

## 👨‍💼 Admin Module

- Admin Login
- Admin Dashboard
- View Customer Accounts
- Create ATM / Customer Account
- View Account Details
- Delete Account
- Generate ATM Card
- Renew Card
- Manage Customer Information
- View Transaction / Passbook Information

---

# 🔐 Security & Encryption

Security is an important part of this project.

The application is designed to protect sensitive banking information through authentication and encryption-related mechanisms.

### Security Features

- Secure login authentication
- PIN-based authentication
- Security question verification
- Date of birth verification
- Encrypted sensitive information where implemented
- Database-backed authentication
- Input validation
- Exception handling
- Controlled access to Admin and Customer modules

> **Security Note:** Never commit real passwords, database credentials, encryption keys, API keys, or real customer information to GitHub.

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| ☕ Java | Application Development |
| 🖥️ Java Swing | Graphical User Interface |
| 🔌 JDBC | Database Connectivity |
| 🗄️ MySQL | Database Management |
| 🔐 Java Cryptography / Encryption | Protection of Sensitive Data |
| 💻 NetBeans | Development Environment |
| 🔧 Git | Version Control |
| 🌐 GitHub | Source Code Management |

---

# 🧠 Core Concepts Used

- Object-Oriented Programming (OOP)
- Encapsulation
- Inheritance
- Polymorphism
- Exception Handling
- JDBC
- SQL
- CRUD Operations
- Database Management
- Authentication
- Encryption
- Input Validation
- Event-Driven Programming
- Transaction Processing
- Modular Programming

---

# 🏗️ System Architecture

```text
                    ATM SIMULATOR
                         │
          ┌──────────────┴──────────────┐
          │                             │
        ADMIN                        CUSTOMER
          │                             │
     Admin Login                   Customer Login
          │                             │
          ▼                             ▼
   Admin Dashboard                Authentication
          │                             │
    ┌─────┼─────┐                       ▼
    │     │     │                    ATM Menu
    │     │     │                       │
  Users Cards Accounts          ┌────────┼────────┐
    │     │     │                │        │        │
    ▼     ▼     ▼             Balance  Withdraw  Deposit
                                  │        │        │
                                  └────────┼────────┘
                                           │
                                      Transactions
                                           │
                                           ▼
                                      MySQL Database
