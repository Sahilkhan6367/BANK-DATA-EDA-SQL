---

# 🏦 MyBank Database Management System

## 📘 Introduction

The **MyBank Database Project** is a structured SQL-based database system designed to manage the day-to-day operations of a modern bank.
It provides an efficient way to store, retrieve, and analyze data related to customers, accounts, loans, transactions, credit cards, ATMs, and branches.

This project demonstrates how a **relational database management system (RDBMS)** can be used to handle complex financial data using **SQL queries** and relationships.

---

## 🎯 Objective

The main objective of this project is to:

* Design and manage a **banking database** using SQL.
* Implement **data relationships** between multiple entities.
* Perform **data analysis** using SQL queries.
* Gain a clear understanding of **real-world banking operations** through database design.

---

## 🧱 Project Description

The **MyBank Database** includes multiple interconnected tables that represent different banking entities:

### 1. **Customers Table**

* Stores personal information of all bank customers such as name, age, and customer ID.
* Acts as a primary table linking to other entities like Accounts, Loans, and Credit Cards.

### 2. **Accounts Table**

* Contains details about all customer accounts such as account number, account type, balance, and status (Active/Inactive).
* Each account is associated with a customer.

### 3. **Transactions Table**

* Records all the banking transactions such as deposits, withdrawals, and transfers.
* Helps in tracking financial activities of each account over time.

### 4. **Loans Table**

* Stores details about customer loans including loan amount, interest rate, start date, end date, and loan status.
* Helps the bank monitor active and completed loans.

### 5. **CreditCards Table**

* Manages information about customer credit cards such as card number, credit limit, balance, and credit utilization.
* Useful for analyzing spending limits and outstanding balances.

### 6. **Branches Table**

* Contains information about various branches of the bank such as location and branch codes.

### 7. **ATMs Table**

* Includes data related to ATM locations and their operational status (Active, Out of Service, etc.).

---

## ⚙️ Functionalities Covered

The project demonstrates a wide range of SQL operations, including:

### 🔹 **Data Retrieval**

* Extracting customer and account information.
* Displaying all transactions and loans.
* Retrieving data based on specific conditions (e.g., active accounts, high-value loans).

### 🔹 **Data Analysis**

* Calculating total loan amounts, credit limits, and transaction values.
* Finding average age of customers and loan interest rates.
* Grouping and categorizing data (e.g., customers by age group).

### 🔹 **Data Manipulation**

* Inserting new customer or account records.
* Deleting inactive accounts.
* Updating customer or account status.

### 🔹 **Relationships and Joins**

* Combining data from multiple tables using **JOIN** operations to show complete information (e.g., customers with their accounts or transactions).

### 🔹 **Subqueries and Nested Queries**

* Finding specific data such as the *second highest loan amount* or *5th highest loan* using subqueries.

### 🔹 **String and Date Functions**

* Extracting specific parts of data such as first name, last name, or date differences.
* Displaying current date and time.
* Calculating days remaining to repay a loan.

---

## 📊 Project Importance

This project is important because it reflects how **real banking systems** operate behind the scenes.
Every financial institution requires a strong database to handle millions of transactions securely and efficiently.

By working on this project, you understand:

* How banking data is structured.
* How relationships are established between customers, accounts, and transactions.
* How to extract useful insights from large datasets using SQL.

---

## 🧠 Key Learnings

Through this project, you will learn:

1. **Database Design:**
   How to create and connect multiple tables using primary and foreign keys.

2. **Data Integrity:**
   Maintaining accurate and consistent data across all entities.

3. **SQL Operations:**
   Writing queries for data retrieval, aggregation, and analysis.

4. **Real-world Problem Solving:**
   Handling real banking scenarios such as credit limit tracking, loan management, and account monitoring.

5. **Optimization Skills:**
   How to write efficient queries using filters, joins, and indexing logic.

---

## 💡 Real-Life Applications

* Used by **banks and financial institutions** for maintaining large customer databases.
* Helpful in **data analytics and reporting** for financial decision-making.
* Can be integrated with **front-end banking applications**.
* Forms the foundation for **Machine Learning models** in credit scoring or fraud detection.

---

## 🚀 Future Enhancements

* Implement **Stored Procedures** for automated tasks.
* Add **Triggers** for auditing transactions.
* Create **Views** for generating reports.
* Connect the database to a **Python/Django** or **Power BI dashboard** for visualization.
* Include **security and encryption** features for sensitive data.

---


