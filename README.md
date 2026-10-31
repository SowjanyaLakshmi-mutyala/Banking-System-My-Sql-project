# 🏦 Banking Management System Using SQL

**Name:** Sowjanya Lakshmi Mutyala  
**Institute:** Codegnan  
**Batch:** JFS-ONR-004  
**Domain:** Database Management System Using MySQL  
**Project:** Banking Management System  

---

## 📝 Project Overview

The Banking Management System is a database mini-project developed using SQL and MySQL. This project is designed to store, organize, and manage banking-related information efficiently.

The database consists of six main tables: Customers, Accounts, Transactions, Branches, Loans, and Employees.

This project demonstrates practical implementation of SQL concepts such as database creation, table creation, primary keys, foreign keys, data insertion, filtering, aggregate functions, GROUP BY, HAVING, ORDER BY, JOINS, and subqueries.

## 🎯 Objectives

- Design and develop a relational database for banking operations.
- Store and manage customer information.
- Maintain account details and account balances.
- Record credit and debit transactions.
- Manage bank branches and employee information.
- Store loan details and interest rates.
- Retrieve information using SQL queries.
- Analyze banking data using aggregate functions.
- Establish relationships between tables using primary and foreign keys.

## 📊 Database Description

The project consists of six main tables:

| Table Name | Description |
|---|---|
| Customers | Stores customer details such as name, address, phone, email, and date of birth. |
| Accounts | Stores account ID, customer ID, branch ID, account type, balance, and creation date. |
| Transactions | Stores transaction ID, account ID, transaction amount, transaction type, and date. |
| Branches | Stores branch ID, branch name, and branch location. |
| Loans | Stores loan ID, customer ID, loan amount, loan type, interest rate, and loan dates. |
| Employees | Stores employee ID, branch ID, employee name, designation, and salary. |

## 🛠️ Tools & Technologies Used

- **Database:** MySQL
- **Language:** SQL
- **IDE:** MySQL Workbench
- **Database Concepts:** Relational Database Management System (RDBMS)
- **Constraints:** PRIMARY KEY, FOREIGN KEY, NOT NULL
- **Aggregate Functions:** COUNT(), SUM(), AVG(), MAX(), MIN()
- **Clauses:** WHERE, GROUP BY, HAVING, ORDER BY
- **Joins:** INNER JOIN
- **Subqueries:** Nested SELECT statements

## 🧪 SQL Concepts Implemented

### 1. Database and Table Creation
- Created the BankingSystem database.
- Created six relational tables.
- Defined primary keys and foreign keys.
- Established relationships between the tables.

### 2. Data Insertion
- Inserted sample customer records.
- Added bank branch details.
- Inserted account information.
- Added credit and debit transactions.
- Inserted loan and employee details.

### 3. Data Retrieval
Implemented SELECT queries to:
- Display all customer records.
- Retrieve customer names, phone numbers, and email addresses.
- Display customers from Hyderabad.
- Retrieve savings accounts.
- Display accounts with balances greater than ₹50,000.

### 4. Filtering and Sorting
Used WHERE and ORDER BY clauses to:
- Filter credit transactions.
- Retrieve employees earning more than ₹40,000.
- Find customers born after a specific date.
- Sort accounts in descending order of balance.

### 5. Aggregate Functions
Implemented aggregate functions to:
- Count the total number of customers.
- Calculate the total account balance.
- Find the average account balance.
- Identify the highest and lowest account balances.

### 6. GROUP BY and HAVING
- Count the number of accounts for each account type.
- Calculate the total balance for each account type.
- Display account types whose total balance exceeds ₹80,000.

### 7. JOIN Operations
Used INNER JOIN to retrieve information from multiple related tables.

Examples:
- Display customer names along with account details.
- Retrieve customer names and their transaction information.
- Display customer loan details.
- Retrieve employee details along with branch information.

### 8. Subqueries
Implemented subqueries to retrieve customers whose account balance is greater than the average balance of all accounts.

## 📈 Results & Analysis

The Banking Management System successfully demonstrates the implementation of relational database concepts using MySQL.

The project provides the following results:

- Successfully created six related banking tables.
- Established relationships using primary and foreign keys.
- Retrieved customer, account, transaction, loan, branch, and employee details.
- Analyzed account balances using aggregate functions.
- Grouped account records based on account types.
- Retrieved information from multiple tables using JOIN operations.
- Compared individual account balances with the average balance using subqueries.


## 🚀 How to Run the Project

1. Install MySQL Server and MySQL Workbench.
2. Open MySQL Workbench.
3. Create the database using the CREATE DATABASE statement.
4. Select the database using the USE statement.
5. Create all six tables.
6. Insert the sample records into the respective tables.
7. Execute the SQL queries one by one.
8. Verify the results in the output section of MySQL Workbench.

## 📂 Project Structure

```text
Banking-Management-System/
│
├── README.md
│
└── BankingManagementSystem.sql
```

## 🙌 Acknowledgments

I would like to thank **Codegnan** and my mentor for providing the opportunity to work on this SQL mini-project.

This project helped me improve my understanding of SQL queries, relational database design, table relationships, and data retrieval using MySQL.

## 📤 Project Output

*Screenshots of SQL queries and their execution results can be added here.*

---
<img width="1615" height="991" alt="image" src="https://github.com/user-attachments/assets/7976dfb2-8571-4d54-82a2-bae7b1834684" />


## 🏷️ Technologies & Tags

#SQL #MySQL #BankingManagementSystem #DBMS #DatabaseProject #SQLQueries #MySQLWorkbench
