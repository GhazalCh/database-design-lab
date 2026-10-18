# Database Design Lab

A university coursework project developed as part of an undergraduate Database Design Laboratory course.

The project explores relational database concepts and SQL programming through a sample university database containing information about students, professors, courses, academic majors, colleges, course registrations, and tuition records.

## Project Overview

The database represents a simplified university information system. It organizes academic information into related tables and includes SQL queries and database programming constructs for retrieving and managing information.

The project demonstrates practical applications of relational database concepts using Microsoft SQL Server-compatible SQL syntax.

## Database Components

The project includes the following database entities:

| Table           | Description                                                                                      |
| --------------- | ------------------------------------------------------------------------------------------------ |
| `Students`      | Stores student information, including names, student identifiers, majors, and academic averages. |
| `Professors`    | Stores professor information, including names, specializations, and academic degrees.            |
| `Course`        | Contains course information, including course names, credit units, and associated professors.    |
| `Major`         | Stores academic major information.                                                               |
| `UnitSelection` | Records course selections, academic terms, student identifiers, and scores.                      |
| `College`       | Stores college information, including names and locations.                                       |
| `Tuition`       | Contains tuition-related records associated with students and academic terms.                    |

## SQL Features

The SQL script covers several database programming concepts:

* Table creation and primary key definitions
* Sample data insertion
* Stored procedures for database operations
* User-defined functions for retrieving information
* Views for presenting query results
* JOIN operations across related tables
* Filtering, grouping, and distinct-value selection
* Queries involving students, professors, courses, and academic records

## Technologies

* Microsoft SQL Server
* Transact-SQL (T-SQL)
* Relational Database Management Systems

## Project Structure

```text
Database-Design-Lab/
├── README.md
├── sql/
│   └── database-design-lab.sql
```

The `docs/` directory is optional and can be omitted if no additional documentation is provided.

## Getting Started

### Prerequisites

To work with the SQL script, you will need:

* Microsoft SQL Server
* SQL Server Management Studio (SSMS), or another compatible SQL editor

### Setup

1. Install and configure Microsoft SQL Server.
2. Open SQL Server Management Studio and connect to your database server.
3. Create a database for the project.
4. Open `sql/database-design-lab.sql` in the SQL editor.
5. Review the script and execute the statements in the appropriate order.
6. Inspect the resulting tables, database objects, and query results.

**Important:** Review the SQL script before execution. The submitted version contains commented-out statements and may require uncommenting and validation before it can be executed as a complete database setup script.

## Learning Objectives

This project provides practical experience with:

* Organizing information in relational tables
* Defining primary keys and identifying relationships between entities
* Writing SQL statements for data retrieval and manipulation
* Using joins to retrieve information from multiple tables
* Creating stored procedures, user-defined functions, and views
* Exploring SQL-based solutions to academic information management tasks

## Academic Context

This repository presents an undergraduate coursework project completed as part of a Database Design Laboratory course.

It is intended for educational purposes and as part of an academic programming portfolio.

## Author

**Ghazal Cheraghi**

Undergraduate Coursework — Database Design Laboratory
