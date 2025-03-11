# 🗃️ Introduction to Databases 📊

## Why Databases Matter
Our modern world is filled with data, guiding us in making important decisions. When working with large amounts of data, we need to know how to store it, so it's organized and quick to access and process. The solution is through databases, and that's what we'll explore here! 🌟

## Defining a Database
A database is an organized collection of information or data. Databases are often compared to spreadsheets. While spreadsheets are convenient for small teams, databases can be accessed by multiple people simultaneously and store massive amounts of data. 💾

## Security Analyst Use Cases 🛡️
As a security analyst, you'll often access databases containing useful information, such as login attempts, software updates, or machine ownership details. Databases enable us to store large amounts of data while keeping it quick and easy to access.

## Relational Databases 🔗
In this course, we'll work with relational databases. A relational database is a structured database containing tables that are related to each other. Let's dive into what makes a relational database special.

### Understanding Tables
Each table contains fields of information, also known as columns. For example, in an employee table, fields might include `employee_id`, `device_id`, and `username`. Tables also contain rows, also called records, which are filled with specific data related to the columns. 🗂️

## Relating Tables with Keys 🔑
Relational databases often have multiple tables. We can connect these tables if they share a common column, known as keys. There are two types of keys:

### Primary Key
- A column where every row has a unique entry.
- Must not have duplicate or empty values.
- Uniquely identifies every row in the table. 

### Foreign Key
- A column in one table that is a primary key in another table.
- Can have empty values and duplicates.
- Connects two tables together.

For example, an `employee_id` column can be a primary key in the employees table and a foreign key in the machines table. A table can have only one primary key but multiple foreign keys.

## Getting Started with SQL 💻
Now that we understand the basics of relational databases, we're ready to move on to SQL, the language that lets us work with databases. Throughout this section, we'll gain hands-on experience with these concepts.

