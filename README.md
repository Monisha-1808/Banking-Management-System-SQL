💳 Banking Management System with Fraud Detection & Analytics using SQL
📖 Project Overview

This project is a comprehensive Banking Management System developed using MySQL to simulate real-world banking operations. The system manages customers, accounts, transactions, loans, cards, employees, and beneficiaries while providing analytical and fraud detection capabilities using advanced SQL techniques.

The project demonstrates database design, relational modeling, business reporting, transaction analysis, and fraud detection commonly used in modern banking systems.

🎯 Project Objectives
Design a normalized banking database.
Manage customer and account information.
Track banking transactions.
Monitor loans and repayments.
Manage debit and credit cards.
Generate analytical reports.
Detect suspicious and fraudulent activities.
Demonstrate advanced SQL concepts.

🏗️ Database Schema
Total Tables: 19
Table Name	Purpose
Branches	Stores branch information
EmployeeRoles	Stores employee roles
AccountTypes	Stores account categories
TransactionTypes	Stores transaction categories
LoanTypes	Stores loan categories
Customers	Stores customer details
CustomerAddresses	Stores customer addresses
CustomerContacts	Stores customer contact information
Employees	Stores employee details
Accounts	Stores bank account information
Beneficiaries	Stores beneficiary details
Transactions	Stores transaction records
Loans	Stores loan details
LoanPayments	Stores EMI/payment records
DebitCards	Stores debit card details
CreditCards	Stores credit card details
LoginHistory	Stores login activities
Notifications	Stores customer notifications
Statements	Stores account statement summaries
🔑 Database Constraints Used
Constraint	Usage
PRIMARY KEY	Unique identification of records
FOREIGN KEY	Relationship between tables
AUTO_INCREMENT	Automatic ID generation
NOT NULL	Mandatory fields
UNIQUE	Prevent duplicate values
DEFAULT	Assign default values
📊 Dataset Statistics
Entity	Records
Customers	50
Employees	20
Accounts	100
Loans	50
Loan Payments	150
Debit Cards	100
Credit Cards	100
Beneficiaries	100
Transactions	500
Branches	5
Employee Roles	5
Account Types	3
Transaction Types	3
Loan Types	3

Total Records: 1100+

🧠 SQL Concepts Implemented
Joins
Query Type
INNER JOIN
LEFT JOIN
RIGHT JOIN
Multi-Table JOIN
Aggregate Functions
Function
COUNT()
SUM()
AVG()
MIN()
MAX()
Subqueries
Type
Single Row Subquery
Multi Row Subquery
Correlated Subquery
Nested Subquery
String Functions
Function
CONCAT()
UPPER()
LOWER()
LENGTH()
SUBSTRING()
Window Functions
Function
ROW_NUMBER()
RANK()
DENSE_RANK()
PARTITION BY
OVER()
Database Programming
Feature
Stored Procedures
Triggers
Views

🚨 Fraud Detection Analytics

The project includes SQL-based fraud detection scenarios such as:

Fraud Detection Scenario	Description
High Value Transactions	Detect unusually large transactions
Frequent Transactions	Multiple transactions in short duration
Excessive Withdrawals	Customers exceeding withdrawal thresholds
Suspicious Account Activity	Accounts with abnormal transaction patterns
High Risk Customers	Customers with unusually high transaction volumes
Duplicate Beneficiary Transfers	Repeated transfers to same beneficiary
Rapid Fund Movement	Multiple transfers across accounts within short intervals

📈 Banking Analytics Reports

The project generates analytical reports including:

Top Account Holders by Balance
Branch-wise Revenue Analysis
Loan Distribution Reports
Monthly Transaction Summary
Customer Account Statistics
Loan Repayment Performance
Card Utilization Analysis
Customer Activity Analysis
🛠️ Technologies Used
Technology	Purpose
MySQL	Database Management
MySQL Workbench	Database Development
Git	Version Control
GitHub	Project Hosting
📂 Project Structure
Banking-Management-System-SQL
│
├── Database
│   ├── 01_Create_Tables.sql
│   ├── 02_Master_Data.sql
│   └── 03_Insert_Data.sql
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
🎓 Learning Outcomes

Through this project, I gained hands-on experience in:

Relational Database Design
Database Normalization
Data Integrity Enforcement
Advanced SQL Querying
Window Functions
Stored Procedures
Triggers
Fraud Detection Analytics
Banking Data Analysis
Real-World Banking Database Modeling

👩‍💻 Author

Monisha B
Graduate Fresher B.E. Artificial Intelligence & Machine Learning
Aspiring Java Full Stack Developer | SQL Enthusiast | Spring Boot Learner
