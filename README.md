# 📗 MySQL Mastery

Welcome to **MySQL Mastery** — a comprehensive collection of SQL queries and concepts organized by difficulty levels to help you build strong MySQL skills.

This repository contains practical examples from basic SELECT statements to advanced joins, subqueries, and date functions, making it ideal for beginners and intermediate learners.

---

## 📚 Contents

The queries are grouped into the following categories:

- Level 1: Basic SELECT Queries  
- Level 2: WHERE, LIKE, IN, BETWEEN  
- Level 3: Aggregate Functions  
- Level 4: GROUP BY and HAVING  
- Level 5: JOINs  
- Level 6: Subqueries  
- Level 7: Set Operations  
- Level 8: DML + Advanced Conditions  
- Level 9: Date Functions & Aliasing  

---

## 🔹 Level 1: Basic SELECT Queries

- Select all columns from a table `Employees`.
- Retrieve only the `name` and `salary` columns.
- Select employees with salary greater than 50000.
- Get employees in the "IT" department.
- Employees whose names start with 'A' or end with 'n'.
- Employees aged between 25 and 35.
- Find employees with NULL values in the `bonus` column.
- Get distinct department names.
- Sort employees by salary in descending order.

---

## 🔹 Level 2: WHERE, LIKE, IN, BETWEEN

- Find employees not in the "HR" department.
- Select employees with names longer than 5 characters.
- Employees with salary between 40000 and 60000.
- Employees working in 'IT', 'Finance', or 'Sales'.
- Employees whose names contain 'an'.

---

## 🔹 Level 3: Aggregate Functions

- Total number of employees.
- Average salary of employees.
- Highest salary.
- Lowest age.
- Total salary paid by each department.

---

## 🔹 Level 4: GROUP BY and HAVING

- Count employees in each department.
- Departments with more than 5 employees.
- Average salary per department where average salary > 50000.
- Count employees by age.
- Max salary per department.

---

## 🔹 Level 5: JOINs

- List employees with their department names (INNER JOIN).
- Show all departments even without employees (LEFT JOIN).
- Employees without any department (LEFT JOIN with NULL check).
- Simulate FULL OUTER JOIN using UNION.
- Count employees in each department using JOIN.

---

## 🔹 Level 6: Subqueries

- Employees earning more than average salary.
- Employees with the second highest salary.
- Employees in departments managed by 'Mr. A'.
- Departments with no employees.
- Employees earning more than 'John'.

---

## 🔹 Level 7: DML + Advanced Conditions

- Increase all employees' salary by 10%.
- Delete employees older than 60.
- Insert a new employee with current date.
- Increase bonus by 1000 for 'Sales' employees.
- Change department of employees named 'Alice' to 'HR'.

---

## 🔹 Level 8: Date Functions & Aliasing

- Employees who joined in the last 6 months.
- Employee names with number of years worked.
- Employees with birthdays in the current month.
- Employee names with alias "Employee Name".
- Format join date as `dd-mm-yyyy`.

---

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/manasipatil17/MySQL-Mastery.git
   cd MySQL-Mastery
