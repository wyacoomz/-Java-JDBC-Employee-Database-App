# Java JDBC – Employee Database App

## Description
This is a simple Java console application that connects to a MySQL database and performs basic CRUD operations (Create, Read, Update, Delete) on an `employees` table using JDBC.

## Features
- Add employee
- View all employees
- Update employee
- Delete employee

## Technologies Used
- Java
- JDBC
- MySQL

## Setup Instructions

1. **Create Database and Table** in MySQL:

```sql
CREATE DATABASE employeedb;

USE employeedb;

CREATE TABLE employees (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100),
    department VARCHAR(100),
    salary DOUBLE
);
