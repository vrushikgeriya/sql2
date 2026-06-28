# SQL Task 2 – Database Operations Project

##  Overview

This project demonstrates basic to intermediate SQL concepts using a simple database system. It includes table creation, data insertion, and multiple queries covering joins, subqueries, string functions, date functions, and window functions.

---

## Database Setup

### Database Name:

`task2`

### Tables Created:

* **customers**
* **orders**
* **employees**

---

##  Table Structures

### 1. Customers Table

Stores customer details:

* CustomerId (Primary Key)
* FirstName
* LastName
* Email
* RegistrationDate

---

### 2. Orders Table

Stores order-related data:

* OrderID (Primary Key)
* CustomerID (Foreign Key reference)
* OrderDate
* TotalAmount

---

### 3. Employees Table

Stores employee information:

* EmployeeID (Primary Key)
* FirstName
* LastName
* Department
* HireDate
* Salary

---

##  Operations Performed

### Joins

* INNER JOIN
* LEFT JOIN
* RIGHT JOIN
* FULL OUTER JOIN

---

###  Subqueries

* Customers with orders above average amount
* Employees with salary above average

---

###  Date Functions

* Extract year and month from OrderDate
* Calculate difference between dates
* Format date into readable format

---

### String Functions

* Concatenate first and last name
* Replace part of a string
* Convert text to upper/lowercase
* Trim extra spaces

---

### Advanced SQL

* Running total using window function
* Ranking orders using `RANK()`
* Conditional logic using `CASE`

  * Discount calculation
  * Salary categorization

---

##  SQL Concepts Used

* `JOIN` (INNER, LEFT, RIGHT, FULL)
* `SUBQUERY`
* Aggregate Functions (`AVG`, `SUM`)
* Date Functions (`YEAR`, `MONTH`, `DATEDIFF`, `DATE_FORMAT`)
* String Functions (`CONCAT`, `REPLACE`, `UPPER`, `LOWER`, `TRIM`)
* Window Functions (`RANK`, `SUM OVER`)
* Conditional Statements (`CASE`)

