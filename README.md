# E-Commerce Customer Churn Analysis

## Module End Assignment 2 — MySQL

### Project Objective

The objective of this project is to **clean, transform, and analyze e-commerce customer data using MySQL** to understand customer churn patterns and customer behavior.

The project includes:

- Data cleaning and missing value handling
- Outlier removal
- Handling data inconsistencies
- Data transformations
- Customer churn analysis
- Customer behavior analysis
- Warehouse-to-home distance categorization
- Customer returns analysis

### Key Analysis

The SQL queries analyze:

- Churned and active customers
- Customer tenure and cashback
- Complaints and churn
- City tiers
- Preferred payment modes
- Order behavior
- Coupon usage
- App usage
- Satisfaction scores
- Cashback by order category
- Warehouse-to-home distance
- Customer returns

### Distance Categories

| Distance | Category |
|---|---|
| `<= 5 km` | Very Close Distance |
| `<= 10 km` | Close Distance |
| `<= 15 km` | Moderate Distance |
| `> 15 km` | Far Distance |

### SQL Concepts Used

`SELECT` · `WHERE` · `GROUP BY` · `ORDER BY` · `HAVING` · `CASE` · `IFNULL` · `AVG()` · `SUM()` · `COUNT()` · `MAX()` · `DISTINCT` · `UPDATE` · `DELETE` · `ALTER TABLE` · `INNER JOIN` · Subqueries

### Tools

**MySQL**

### Project Workflow

`Dataset → Data Cleaning → Data Transformation → Data Exploration & Analysis → Customer Returns Analysis`

### Output

The project produces SQL-based results showing **customer churn status, payment preferences, order and coupon behavior, satisfaction levels, cashback patterns, customer distance categories, and return details**.

These outputs help demonstrate how SQL can be used to extract meaningful information from e-commerce customer data.

### Repository Structure

E-Commerce-Customer-Churn-Analysis/
├── E-Commerce Customer churn db.sql
├── Module End Assignment 2_MySQL_E-Commerce Customer Churn Analysis.pdf
└── README.md
