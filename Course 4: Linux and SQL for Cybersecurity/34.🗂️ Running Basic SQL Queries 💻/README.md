# 🗂️ Running Basic SQL Queries 💻

## Introduction
In this note, we're going to run our very first SQL query! This query will be based on a common work task that you might encounter as a security analyst. 🌟

### Task: Determining Assigned Computers 🖥️
Let's say we have access to the `employees` table, which has five columns. Two of them, `employee_id` and `device_id`, contain the information we need. We'll write a query to this table that returns only these two columns. 🚀

## Key SQL Keywords 🔑
The two SQL keywords we need for basic queries are `SELECT` and `FROM`. 
- **SELECT**: Indicates which columns to return.
- **FROM**: Indicates which table to query.

### Practical Example 🎯
Using these keywords in SQL is very similar to how we would use these words in everyday language. For example, you might ask a friend to select apples and bananas from the big box when shopping for fruit. Let's use `SELECT` and `FROM` in SQL to return the information we need on employees and their computers.

```sql
SELECT employee_id, device_id
FROM employees;
