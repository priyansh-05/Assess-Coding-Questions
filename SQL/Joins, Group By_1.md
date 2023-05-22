# Q1 - SQL Coding Question

## Schema

Table 1: Employees

| Column Name | Data Type |
| --- | --- |
| EmployeeID | int |
| FirstName | varchar |
| LastName | varchar |
| HireDate | date |
| Salary | float |
| DepartmentID | int |

Table 2: Departments

| Column Name | Data Type |
| --- | --- |
| DepartmentID | int |
| DepartmentName | varchar |
| ManagerID | int |
| Location | varchar |

## Query

Write a SQL query to retrieve the total number of employees in each department. The output should have the following columns:

| Column Name | Description |
| --- | --- |
| DepartmentID | The ID of the department |
| DepartmentName | The name of the department |
| TotalEmployees | The total number of employees in the department |

The query should return the results in ascending order of the DepartmentID column.
