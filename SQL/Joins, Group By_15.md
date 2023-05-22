# **Q29 - SQL Coding Question**

## **Schema**

Table 1: Sales

| Column Name | Data Type |
| --- | --- |
| SaleID | int |
| SalespersonID | int |
| CustomerID | int |
| SaleDate | date |
| Amount | float |

Table 2: Salespeople

| Column Name | Data Type |
| --- | --- |
| SalespersonID | int |
| FirstName | varchar |
| LastName | varchar |
| HireDate | date |
| Salary | float |

## **Query**

Write a SQL query to retrieve the name of the salesperson with the highest total sales. The output should have the following columns:

| Column Name | Description |
| --- | --- |
| SalespersonName | The name of the salesperson |
| TotalSales | The total sales made by the salesperson |
