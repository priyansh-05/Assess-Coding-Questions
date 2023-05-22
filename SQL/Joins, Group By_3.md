# Q3 - SQL Coding Question

## Schema

Table 1: Students

| Column Name | Data Type |
| --- | --- |
| StudentID | int |
| FirstName | varchar |
| LastName | varchar |
| DateOfBirth | date |
| Gender | varchar |

Table 2: Enrollments

| Column Name | Data Type |
| --- | --- |
| EnrollmentID | int |
| StudentID | int |
| CourseID | int |
| Grade | varchar |

Table 3: Courses

| Column Name | Data Type |
| --- | --- |
| CourseID | int |
| CourseName | varchar |
| Credits | int |
| Department | varchar |

## Query

Write a SQL query to retrieve the average grade of each course. The output should have the following columns:

| Column Name | Description |
| --- | --- |
| CourseID | The ID of the course |
| CourseName | The name of the course |
| AverageGrade | The average grade of the course |

The query should return the results in ascending order of the CourseID column.
