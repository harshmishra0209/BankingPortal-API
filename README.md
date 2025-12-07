# BankingPortal-API
🏦 Banking Portal REST API

A secure and scalable Banking Portal REST API built using Spring Boot, Spring Security, and JWT Authentication.
This project provides core banking features such as account management, fund transfer, customer authentication, and transaction history.

📌 Features
🔐 Authentication & Authorization

User registration and login

JWT-based authentication

Role-based access control:

USER → view balance, transfer money, view transactions

ADMIN → create accounts, view all users

🧑‍💼 Customer Module

Register new customer

Login using email & password

Update profile

View customer details

🏦 Account Management

Admin can create customer accounts

Customers can view their account details

Check available balance

💸 Fund Transfer

Transfer money between accounts

Validations:

Sufficient balance

Valid account number

Creates debit/credit transactions automatically

📜 Transaction History

View all transactions for an account

Tracks type (DEBIT/CREDIT), timestamp, amount, and reference

⚠️ Error Handling

User not found

Invalid credentials

Insufficient balance

Account not found

Global exception handler

🏗 Tech Stack
Layer	Technology
Backend Framework	Spring Boot
Security	Spring Security + JWT
Database	MySQL
ORM	Spring Data JPA / Hibernate
Build Tool	Maven
Language	Java 17
