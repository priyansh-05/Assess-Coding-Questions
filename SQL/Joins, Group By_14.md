# **Q30 - SQL Coding Question**

## **Schema**

Table 1: Customers

| Column Name | Data Type |
| --- | --- |
| CustomerID | int |
| FirstName | varchar |
| LastName | varchar |
| Gender | varchar |
| Email | varchar |
| Phone | varchar |
| Address | varchar |

Table 2: Orders

| Column Name | Data Type |
| --- | --- |
| OrderID | int |
| CustomerID | int |
| OrderDate | date |
| TotalAmount | float |

## **Query**

Write a SQL query to retrieve the name of the customer with the highest total order amount. The output should have the following columns:

| Column Name | Description |
| --- | --- |
| CustomerName | The name of the customer |
| TotalOrderAmount | The total amount spent by the customer |
