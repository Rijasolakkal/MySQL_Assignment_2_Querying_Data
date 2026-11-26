# MySQL_Assignment_2_Querying_Data
MySQL Querying data 
# MySQL Assignment – SQL Queries, Aggregate Functions, GROUP BY, HAVING & Joins

## Project Overview
This assignment focuses on practising SQL queries using MySQL Workbench. The objective is to retrieve, filter, sort, summarise, and combine employee-related data from multiple tables.

## 🛠️ Tools Used
- MySQL
- MySQL Workbench

## Database Tables
The assignment uses the following tables:

- **Employees** – Employee details such as employee ID, name, gender, age, hire date, designation, salary, department ID, and location ID.
- **Departments** – Department details, including department ID and department name.
- **Location** – Location details, including location ID and location name.

## Concepts Practised

### 1. SELECT, WHERE, ORDER BY & LIMIT
- Retrieved employee records using SELECT.
- Filtered records using WHERE conditions.
- Sorted employees by department and salary.
- Retrieved employees hired within a specified date range.
- Used LIMIT to display a specific number of records.

### 2. Aggregate Functions
Practised aggregate functions to summarise employee data:

- `SUM()` – Calculated total salary for employees in the Finance department.
- `MIN()` – Identified the minimum employee age.

### 3. GROUP BY
- Found the maximum salary for each location.
- Calculated the average salary for each designation containing the word "Analyst".

### 4. HAVING
- Identified departments with fewer than three employees.
- Found locations where female employees had an average age below 30.

### 5. JOINS

**INNER JOIN**
- Retrieved employee names, designations, and department names for employees assigned to departments.

**LEFT JOIN**
- Listed all departments along with their employee counts, including departments with no employees.

**RIGHT JOIN**
- Displayed all locations and the employees assigned to each location, including locations without employees.

## 📸 Screenshots
Screenshots of the SQL queries and their corresponding outputs are included in this repository as evidence of the completed tasks.

## Learning Outcomes

- Writing SQL queries to retrieve and filter data.
- Sorting and limiting query results.
- Using aggregate functions for data analysis.
- Grouping records and filtering grouped results.
- Combining data from multiple tables using INNER JOIN, LEFT JOIN, and RIGHT JOIN.
- Analysing employee, salary, department, and location information.
