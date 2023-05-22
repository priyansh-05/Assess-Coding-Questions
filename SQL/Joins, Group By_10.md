# **Q34 - SQL Coding Question**

## **Schema**

Table 1: Students

| Column Name | Data Type |
| --- | --- |
| StudentID | int |
| FirstName | varchar |
| LastName | varchar |
| Gender | varchar |
| DateOfBirth | date |
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
| SchoolID | int |

## **Query**

Write a SQL query to retrieve the name of the department with the highest number of students. The output should have the following columns:

| Column Name | Description |
| --- | --- |
| DepartmentName | The name of the department |
| NumStudents | The number of students in the department |
