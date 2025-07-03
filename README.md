# Employee Database App (Java + JDBC + MySQL)
This is a simple console-based Java application that performs *CRUD operations* (Create, Read, Update, Delete) on an employee database using *JDBC* and *MySQL*.

## Features
* Add a new employee
* View all employees
* Update employee email
* Delete employee record
  
## Technologies Used
- Java
- MySQL
- JDBC (Java Database Connectivity)
- Eclipse IDE

## 🗄 Database Setup
Before running the app, make sure to create the database and table in MySQL:
```sql

CREATE DATABASE company;
USE company;

CREATE TABLE employees (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100),
    email VARCHAR(100),
    salary DOUBLE
);
