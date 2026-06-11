# 💳 Banking Management System with Fraud Detection using MySQL

## 📖 Project Overview

This project is a comprehensive Banking Management System developed using MySQL to simulate real-world banking operations. The system manages customers, accounts, transactions, loans, cards, employees, and beneficiaries while providing analytical and fraud detection capabilities using advanced SQL techniques. 

The project demonstrates database design, relational modeling, business reporting, transaction analysis, and fraud detection commonly used in modern banking systems.

## 🎯 Objectives

* Design a normalized banking database.
* Manage customer and account information.
* Track transactions and account activities.
* Maintain loan and repayment records.
* Generate banking reports using SQL queries.
* Implement basic fraud detection mechanisms.
* Demonstrate advanced SQL concepts.

## 🏗️ Database Schema

### Total Tables: 19

| Table Name        | Description                 |
| ----------------- | --------------------------- |
| Branches          | Branch information          |
| EmployeeRoles     | Employee role details       |
| AccountTypes      | Account categories          |
| TransactionTypes  | Transaction categories      |
| LoanTypes         | Loan categories             |
| Customers         | Customer information        |
| CustomerAddresses | Customer addresses          |
| CustomerContacts  | Customer contact details    |
| Employees         | Employee records            |
| Accounts          | Bank account information    |
| Beneficiaries     | Beneficiary details         |
| Transactions      | Transaction records         |
| Loans             | Loan information            |
| LoanPayments      | Loan repayment details      |
| DebitCards        | Debit card information      |
| CreditCards       | Credit card information     |
| LoginHistory      | Customer login records      |
| Notifications     | Customer notifications      |
| Statements        | Account statement summaries |

## 🔑 Database Constraints Used

* PRIMARY KEY
* FOREIGN KEY
* AUTO_INCREMENT
* NOT NULL
* UNIQUE
* DEFAULT

## 📊 Dataset Statistics

| Entity        | Records |
| ------------- | ------- |
| Customers     | 50      |
| Employees     | 20      |
| Accounts      | 100     |
| Loans         | 50      |
| Loan Payments | 150     |
| Debit Cards   | 100     |
| Credit Cards  | 100     |
| Beneficiaries | 100     |
| Transactions  | 500     |

**Total Records Managed: 1100+**

## 🧠 SQL Concepts Implemented

### Queries

* Basic SQL Queries
* Joins
* Aggregate Functions
* Subqueries
* String Functions
* Window Functions

### Stored Procedures

* Get Customer Accounts
* Get Customer Loans
* Get Branch Employees
* Get Customer Total Balance

### Triggers

* Transaction Audit Trigger
* Fraud Detection Trigger

## 🚨 Fraud Detection Features

The project includes basic fraud detection using SQL queries and triggers to identify:

* High-value transactions
* Unusual transaction activity
* Potentially suspicious account behavior

## 🛠️ Technologies Used

* MySQL
* MySQL Workbench
* Git
* GitHub
* VS Code

## 📂 Project Structure

Banking-Management-System-SQL
│
├── Database
│   ├── 01_Create_Tables.sql
│   └── 02_Master_Data.sql
│
├── Queries
│   ├── 01_Basic_Queries.sql
│   ├── 02_Joins.sql
│   ├── 03_Aggregate_Functions.sql
│   ├── 04_Subqueries.sql
│   ├── 05_String_Functions.sql
│   ├── 06_Window_Functions.sql
│   └── 07_Fraud_Detection.sql
│
├── Procedures
│   └── Stored_Procedures.sql
│
├── Triggers
│   └── Triggers.sql
│
└── README.md

## 🎓 Learning Outcomes

Through this project, I gained practical experience in:
* Relational Database Design
* Database Normalization
* SQL Query Optimization
* Joins and Subqueries
* Window Functions
* Stored Procedures
* Database Triggers
* Fraud Detection using SQL
* Git and GitHub Version Control

## 👩‍💻 Author

Monisha B
B.E. Artificial Intelligence & Machine Learning
Aspiring Java Full Stack Developer | SQL Enthusiast | Spring Boot Learner
