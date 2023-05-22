# **Q39 - SQL Coding Question**

## **Schema**

Table 1: Students

| Column Name | Data Type |
| --- | --- |
| StudentID | int |
| FirstName | varchar |
| LastName | varchar |
| Email | varchar |
| Address | varchar |
| City | varchar |
| State | varchar |
| ZipCode | varchar |
| Country | varchar |
| MajorID | int |

Table 2: Majors

| Column Name | Data Type |
| --- | --- |
| MajorID | int |
| MajorName | varchar |
| DepartmentID | int |

Table 3: Departments

| Column Name | Data Type |
| --- | --- |
| DepartmentID | int |
| DepartmentName | varchar |
| ChairID | int |

## **Query**

Write a SQL query to retrieve the name of the department with the highest number of students. The output should have the following columns:

| Column Name | Description |
| --- | --- |
| DepartmentName | The name of the department |
| NumStudents | The number of students enrolled in the department |
