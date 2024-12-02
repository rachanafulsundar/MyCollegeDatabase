# MyCollege Database Management System

## Project Overview
This project involves creating and managing the **MyCollege** database using SQL Server Management Studio (SSMS). The database encompasses tables for Courses, Departments, Instructors, Students, Tuition, and StudentCourses. Key tasks include database setup, performing DML operations, creating views, stored procedures, and functions, and designing database diagrams.

---

## Table of Contents
1. [Abstract](#abstract)
2. [Features](#features)
3. [Database Design](#database-design)
4. [Implementation](#implementation)
5. [Essential SQL Skills](#essential-sql-skills)
6. [Advanced SQL Skills](#advanced-sql-skills)
7. [Technologies Used](#technologies-used)
8. [Setup Instructions](#setup-instructions)
9. [How to Use](#how-to-use)
10. [Remarks](#remarks)
11. [Author](#author)

---

## Abstract
This project involves:
- Setting up the MyCollege database.
- Running SQL scripts to perform essential and advanced operations.
- Designing database diagrams to showcase relationships between tables.
- Implementing views, stored procedures, functions, and scripts to manipulate and query the database.

---

## Features
- **Database Setup**: Initialization of the database with pre-defined scripts.
- **DML Operations**: Data manipulation on key tables like Students, Instructors, Courses, etc.
- **Advanced SQL**: Implementation of stored procedures, functions, and scripts for enhanced database management.
- **Database Design**: Creation of ER diagrams and linking tables to define relationships between entities.

---

## Database Design
- **Tables**: Courses, Departments, Instructors, Students, Tuition, StudentCourses.
- **Relationships**:
  - Many-to-Many between Courses and Students resolved using a linking table: `StudentCourses`.
  - One-to-Many between Departments and Courses/Instructors.
  - One-to-Many between Students and StudentCourses.

Additional design:
- **Books and Users**:
  - Many-to-Many relationship between Users and Books resolved using a linking table: `Downloads`.

---

## Implementation
1. **Database Setup**: Scripts provided for creating and initializing tables.
2. **Essential SQL Skills**: Queries for basic CRUD operations.
3. **Advanced SQL Skills**: Includes views, stored procedures, user-defined functions, and scripts.

---

## Essential SQL Skills
- Queries to:
  - Display and manipulate data from tables like Students, Instructors, and Courses.
  - Perform joins, subqueries, and aggregations.
  - Utilize `ROLLUP` for grouped summaries.

---

## Advanced SQL Skills
- **Views**: Predefined queries for fetching instructor details, student courses, and department data.
- **Stored Procedures**: For operations like counting instructors or managing salaries.
- **Functions**: Custom functions for calculating student course units and querying instructor details.
- **Scripts**: Dynamic SQL for advanced operations and condition-based queries.

---

## Technologies Used
- **Database Platform**: SQL Server
- **Tools**: SQL Server Management Studio (SSMS)
- **Programming Language**: SQL

---
