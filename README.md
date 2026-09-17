# Software Management System

## 📌 Project Overview

The **Software Management System** is a DBMS project designed to manage software company information in a structured and organized way.

The system manages employees, departments, clients, projects, tasks, teams, milestones, and resources using relational database concepts.

## 🎯 Objectives

* Organize software company data.
* Manage employee and department information.
* Manage clients and their projects.
* Track project tasks and deadlines.
* Manage project teams.
* Track project milestones.
* Manage resources used by teams.
* Maintain relationships between tables using Primary Keys and Foreign Keys.

## 🗂️ Entities

The database contains 8 main entities:

1. Department
2. Employee
3. Client
4. Project
5. Task
6. Team
7. Milestone
8. Resource

## 🔗 Relationships

| Relationship          | Cardinality |
| --------------------- | ----------- |
| Department → Employee | 1 : N       |
| Client → Project      | 1 : N       |
| Project → Task        | 1 : N       |
| Employee → Task       | 1 : N       |
| Project → Team        | 1 : 1       |
| Project → Milestone   | 1 : N       |
| Team → Resource       | 1 : N       |

## 🛠️ Technologies Used

* SQL
* SQLite
* DBMS
* Relational Database Concepts

## 🔑 Database Concepts Used

* Primary Key
* Foreign Key
* NOT NULL
* UNIQUE
* CREATE TABLE
* INSERT
* SELECT
* JOIN
* WHERE
* GROUP BY
* COUNT
* UPDATE
* DELETE

## 📊 Database Tables

### Department

Stores department details such as department name and location.

### Employee

Stores employee details and connects employees with departments.

### Client

Stores client contact and address information.

### Project

Stores project details, dates, status, and associated clients.

### Task

Stores project tasks and the employees assigned to them.

### Team

Stores teams associated with projects.

### Milestone

Stores important project milestones, deadlines, and status.

### Resource

Stores resources used by project teams.

## 🚀 How to Run

1. Download or clone this repository.
2. Open the `software_management_system.sql` file in an SQLite-compatible SQL editor.
3. Execute the SQL script.
4. The tables and sample records will be created.
5. Run the SELECT queries to view the results.

## 📁 Project Files

* `software_management_system.sql` — Database creation, sample data, and SQL queries.
* `README.md` — Project documentation.
* `Software_Management_System_DBMS_Review1.pptx` — Project presentation.

## 👥 Team

* Shaik Abdul Sattar
* K Naveen Kumar
* K Syam Kumar
* K Harsha Vardhan

## 🎓 Department

Department of Artificial Intelligence & Machine Learning

## 📚 Academic Project

DBMS Cornerstone Project — Software Management System
