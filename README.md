# SQL Common Table Expressions (CTEs) and Window Functions Project

**Registration Number:** 32996/2025

**Student Name:** ASHIMWE Bien Aime Justus

**Course:** Database Programming

**Project Title:** Implementation of Common Table Expressions (CTEs) and SQL Window Functions in Oracle SQL

**Academic Year:** 2025/2026

---

# Project Description

This project demonstrates the implementation of **Common Table Expressions (CTEs)** and **SQL Window Functions** using Oracle SQL. The project is based on an existing database containing the **Customers**, **Commodities**, **Orders**, and **Workers** tables. The objective is to demonstrate how advanced SQL techniques can simplify complex queries, improve data analysis, and support business decision-making.

The project contains SQL queries, explanations of their business value, interpretations of the results, and screenshots of the query outputs.

---

# Database Tables

## Customers

| Column       | Description                |
| ------------ | -------------------------- |
| CustomerID   | Unique customer identifier |
| CustomerName | Name of the customer       |
| City         | Customer's city            |

## Commodities

| Column         | Description                 |
| -------------- | --------------------------- |
| CommodityID    | Unique commodity identifier |
| CommodityTName | Name of the commodity       |
| Price          | Price of the commodity      |

## Orders

| Column      | Description                   |
| ----------- | ----------------------------- |
| OrderID     | Unique order identifier       |
| CustomerID  | Customer who placed the order |
| CommodityID | Commodity ordered             |
| Quantity    | Quantity ordered              |
| OrderDate   | Date of the order             |

## Workers

| Column     | Description                                      |
| ---------- | ------------------------------------------------ |
| WorkerID   | Unique worker identifier                         |
| WorkerName | Name of the worker                               |
| ManagerID  | References the worker's manager (self-reference) |

---

# Project Objectives

* Demonstrate the use of Common Table Expressions (CTEs).
* Implement SQL Window Functions using Oracle SQL.
* Analyze business data using analytical SQL functions.
* Explain the business value of each implementation.
* Interpret query results for business reporting.

---

# Part A – Common Table Expressions (CTEs)

The project implements the following CTEs:

* Simple CTE
* Multiple CTEs
* Recursive CTE (or Oracle Hierarchical Query using `CONNECT BY` when recursive CTEs are unavailable)
* CTE with Aggregation
* CTE combined with JOIN operations

Each implementation includes:

* SQL query with comments
* Business value explanation

---

# Part B – SQL Window Functions

The project demonstrates the following SQL Window Functions.

## Ranking Functions

* ROW_NUMBER()
* RANK()
* DENSE_RANK()
* PERCENT_RANK()

## Aggregate Window Functions

* SUM() OVER()
* AVG() OVER()
* MIN() OVER()
* MAX() OVER()

## Navigation Functions

* LAG()
* LEAD()

## Distribution Functions

* NTILE()
* CUME_DIST()

Each implementation includes:

* SQL query with comments
* Screenshot of the output
* Interpretation of the results

---

# Business Value

The SQL techniques demonstrated in this project provide several business benefits:

* Improve the readability and maintainability of SQL queries.
* Simplify complex data retrieval using Common Table Expressions.
* Analyze customer purchasing behavior and sales performance.
* Identify top-performing customers through ranking functions.
* Calculate running totals, averages, minimums, and maximums.
* Compare previous and future records using navigation functions.
* Group customers into performance categories using distribution functions.
* Represent organizational reporting structures using hierarchical queries.
* Support business intelligence, reporting, and data-driven decision-making.

---

# Software Requirements

* Oracle Database
* Oracle SQL Developer or SQL*Plus

**Note:** Oracle 11g does not support Recursive CTEs. For Oracle 11g, the equivalent hierarchical query (`START WITH ... CONNECT BY PRIOR`) should be used.

---

# Project Structure

```text
Project/
│
├── README.md
├── Part_A_CTEs.sql
├── Part_B_Window_Functions.sql
├── Screenshots/
│   ├── Simple_CTE.png
│   ├── Multiple_CTE.png
│   ├── Recursive_CTE.png
│   ├── ROW_NUMBER.png
│   ├── RANK.png
│   ├── DENSE_RANK.png
│   ├── PERCENT_RANK.png
│   ├── SUM_OVER.png
│   ├── AVG_OVER.png
│   ├── MIN_OVER.png
│   ├── MAX_OVER.png
│   ├── LAG.png
│   ├── LEAD.png
│   ├── NTILE.png
│   ├── CUME_DIST.png
└── Report.pdf
```

---

# How to Run

1. Open Oracle SQL Developer or SQL*Plus.
2. Connect to the Oracle database.
3. Ensure the required tables (`Customers`, `Commodities`, `Orders`, and `Workers`) exist.
4. Execute the SQL scripts for Part A (CTEs).
5. Execute the SQL scripts for Part B (Window Functions).
6. Verify the outputs.
7. Capture screenshots of the results and include them in the project report.

---

# Expected Learning Outcomes

After completing this project, learners should be able to:

* Understand the concept and use of Common Table Expressions.
* Apply SQL Window Functions for analytical processing.
* Write modular and maintainable SQL queries.
* Analyze and interpret business data effectively.
* Produce meaningful reports using Oracle SQL.

---

# Author Information

**Student Name:** ASHIMWE Bien Aime Justus

**Registration Number:** 32996/2025

**Course:** Database Programming

**Academic Year:** 2025/2026

---

# Student Integrity Declaration

I, **ASHIMWE Bien Aime Justus (Registration Number: 32996/2025)**, declare that this project is my own academic work prepared for the **Database Programming** course. All SQL queries, explanations, interpretations, and supporting documentation have been completed honestly and in accordance with my institution's academic integrity requirements. Any external resources used during the preparation of this project have been appropriately acknowledged where applicable.

I understand that plagiarism, unauthorized collaboration, and any form of academic dishonesty are violations of institutional regulations and may result in disciplinary action.


