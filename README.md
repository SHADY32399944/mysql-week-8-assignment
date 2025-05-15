# mysql-week-8-assignment

Project Title:
Student Records Management System using MySQL

Project Description:
This project is a relational database system designed to manage student academic records. It allows storage and management of student information, subjects offered, and student performance (marks) in various subjects. The database is normalized and includes relational integrity constraints such as primary keys, foreign keys, and data validation through NOT NULL, UNIQUE, and CHECK constraints.

The system includes:

A Students table for storing personal details.

A Subjects table for managing courses or subjects.

A Marks table linking students to subjects with their respective scores, showcasing a many-to-many relationship resolved via foreign keys.

This schema can be extended to support grading, attendance, and more.

How to Run / Setup the Project:
Option 1: Using MySQL Command Line
Open the MySQL command-line tool or terminal.

Connect to your MySQL server:

bash
Copy
Edit
mysql -u root -p
Import the SQL file:

sql
Copy
Edit
SOURCE path_to_your_file/student_records.sql;
Use the database:

sql
Copy
Edit
USE StudentRecords;
Option 2: Using MySQL Workbench
Open MySQL Workbench.

Create a new SQL tab and paste the content of student_records.sql into the editor.

Execute the SQL script.

Refresh the schema to view the new tables and data.

Requirements:
MySQL Server installed (v5.7+ recommended)

MySQL Workbench or command-line interface
