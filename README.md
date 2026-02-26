#  SQL for Data Analysis

A comprehensive, hands-on SQL learning repository designed to build strong foundations in data analysis using SQL. This project features structured notebooks covering core SQL concepts, analytical queries, and real-world data manipulation techniques using Jupyter Notebook + MySQL.

 **Note:** This repository documents my personal learning journey in Data Analytics, featuring practical implementations and exercises I've completed to master SQL for data analysis.

---

#  Repository Objective

This repository serves as a complete learning path to:

- Master SQL from basics to intermediate/advanced level  
- Practice real-world analytical queries used across industries  
- Understand data-driven decision making through SQL  
- Integrate SQL with Python for enhanced visualization and experimentation  
- Build a portfolio of SQL skills applicable to data analyst roles  

---

#  Technologies Used

| Technology | Purpose |
|------------|---------|
| SQL | Core query language for data manipulation |
| MySQL | Relational database management system |
| Python | Environment support and data processing |
| Jupyter Notebook | Interactive coding and documentation |
| IPython SQL Magic | Seamless SQL execution within notebooks |

---

#  Repository Structure

```
SQL-for-Data-Analysis/
│
├── 01_Basics_of_SQL.ipynb                    # Introduction to SQL fundamentals
├── 02_Data_Retrieval.ipynb                   # SELECT, sorting, and limiting
├── 03_Filtering_&_Logical_Conditions.ipynb   # WHERE, AND, OR, LIKE operators
├── 04_Aggregate_Functions_&_GROUP_BY.ipynb   # Statistical aggregations
├── 05_Joins.ipynb                            # Combining multiple tables
├── 06_Subqueries.ipynb                       # Nested and correlated queries
├── 07_Window_Functions.ipynb                 # Advanced analytical functions
├── 08_SQL_CTE.ipynb                          # Common Table Expressions
├── 09_CASE_WHEN.ipynb                        # Conditional logic
├── 10_Date_Time_Analysis.ipynb               # Temporal data handling
├── 11_String_Functions.ipynb                 # Text manipulation
└── README.md                                 # Project documentation
```

---

#  Topics Covered

| Module | Topic | Concepts Covered |
|--------|-------|------------------|
| 1️⃣ | **SQL Fundamentals** | Database & table concepts, Schema design basics, Basic query structure, SELECT statements |
| 2️⃣ | **Data Retrieval** | Column selection, ORDER BY, LIMIT / TOP, Column aliasing (AS) |
| 3️⃣ | **Filtering & Logical Conditions** | WHERE clause, AND / OR / NOT, BETWEEN, LIKE & wildcards, IN operator |
| 4️⃣ | **Aggregate Functions & GROUP BY** | COUNT(), SUM(), AVG(), MIN(), MAX(), GROUP BY, HAVING vs WHERE, Multi-level grouping |
| 5️⃣ | **Joins** | INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL OUTER JOIN, CROSS JOIN, Self joins, Multi-table joins |
| 6️⃣ | **Subqueries** | Nested queries, Correlated subqueries, Subqueries in WHERE / FROM / SELECT, EXISTS & IN |
| 7️⃣ | **Window Functions** | ROW_NUMBER(), RANK(), DENSE_RANK(), PARTITION BY, Running totals, LEAD() & LAG() |
| 8️⃣ | **Common Table Expressions (CTE)** | WITH clause, Recursive CTEs, Query readability, Multiple CTE usage |
| 9️⃣ | **CASE WHEN Logic** | Conditional expressions, Data categorization, Derived columns |
| 🔟 | **Date & Time Analysis** | Date extraction, Date arithmetic, Formatting, Time filtering, Period analysis |
| 1️⃣1️⃣ | **String Functions** | CONCAT(), SUBSTRING(), UPPER(), LOWER(), TRIM(), Pattern matching, Data cleaning |

---

#  Key Learning Outcomes

By working through this repository, you will gain:

✅ Proficiency in writing complex SQL queries  
✅ Expertise in data filtering, transformation, and aggregation  
✅ Analytical mindset for deriving insights from datasets  
✅ Deep understanding of relational database concepts  
✅ Problem-solving skills applicable to real-world business scenarios  
✅ Portfolio-ready SQL projects for job applications  

---

#  Getting Started

## Prerequisites

- MySQL Server (8.0 or higher recommended)  
- Python 3.7+  
- Jupyter Notebook  

---

## Installation Steps

### 1️⃣ Install MySQL

Download from: https://www.mysql.com  
Follow installation instructions for your OS.

---

### 2️⃣ Install Python Dependencies

```bash
pip install jupyter notebook ipython-sql mysql-connector-python pandas
```

---

### 3️⃣ Clone Repository

```bash
git clone https://github.com/pranay-surya/SQL.git
cd SQL
```

---

### 4️⃣ Launch Jupyter Notebook

```bash
jupyter notebook
```

---

### 5️⃣ Configure Database Connection

In each notebook, update the connection string:

```python
%load_ext sql
%sql mysql+mysqlconnector://username:password@localhost/database_name
```
