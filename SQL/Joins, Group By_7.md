# **Q37 - SQL Coding Question**

## **Schema**

Table 1: Employees

| Column Name | Data Type |
| --- | --- |
| EmployeeID | int |
| FirstName | varchar |
| LastName | varchar |
| Gender | varchar |
| DateOfBirth | date |
| Salary | float |
| DepartmentID | int |

Table 2: Departments

| Column Name | Data Type |
| --- | --- |
| DepartmentID | int |
| DepartmentName | varchar |
| ManagerID | int |
| Location | varchar |

## **Query**

Write a SQL query to retrieve the name of the department with the highest average salary. The output should have the following columns:

| Column Name | Description |
| --- | --- |
| DepartmentName | The name of the department |
| AvgSalary | The average salary of all employees in the department |
