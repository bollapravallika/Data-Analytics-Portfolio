# Mini ATM System

# Project Overview

The Mini ATM System is a MySQL-based project developed to simulate basic ATM transactions such as deposits and withdrawals.

The project demonstrates the use of Stored Procedures, parameters, conditional logic, validation, and custom error handling in MySQL.

# Technologies Used

- MySQL
- MySQL Workbench
- Stored Procedures
- SQL

# Key Features

- Deposit money
- Withdraw money
- Account balance management
- Account number validation
- Transaction amount validation
- Insufficient balance validation
- Custom error handling

# Database Design

An `accounts` table was created to store account information and account balances.

Key concepts used:

- Primary Key
- DECIMAL data type
- Stored Procedures
- IN Parameters
- Conditional Logic

# Stored Procedures

### sp_deposit

Used to deposit money into an account after validating the account number and transaction amount.

### sp_withdraw

Used to withdraw money after checking:

- Account existence
- Transaction amount
- Available account balance

# Error Handling

Custom validation was implemented using:

```sql
SIGNAL SQLSTATE '45000'
The system handles scenarios such as:

Invalid account number
Zero transaction amount
Negative transaction amount
Insufficient account balance

 Testing
The stored procedures were tested using multiple valid and invalid transaction scenarios to verify:

Successful deposits
Successful withdrawals
Invalid account handling
Invalid transaction amounts
Insufficient balance handling

 Project Objective
The objective of this project is to demonstrate practical knowledge of MySQL Stored Procedures, validation, conditional logic, parameters, and error handling.

 Author

Bolla Pravallika

Data Analyst | SQL | Power BI | Excel
