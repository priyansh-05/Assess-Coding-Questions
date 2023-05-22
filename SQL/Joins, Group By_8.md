# **Q36 - SQL Coding Question**

## **Schema**

Table 1: Customers

| Column Name | Data Type |
| --- | --- |
| CustomerID | int |
| FirstName | varchar |
| LastName | varchar |
| Email | varchar |
| Address | varchar |
| City | varchar |
| State | varchar |
| ZipCode | varchar |
| Country | varchar |

Table 2: Orders

| Column Name | Data Type |
| --- | --- |
| OrderID | int |
| CustomerID | int |
| OrderDate | date |
| TotalAmount | float |
| TaxAmount | float |
| DiscountAmount | float |
| ShippingAmount | float |

## **Query**

Write a SQL query to retrieve the name of the customer with the highest total order amount. The output should have the following columns:

| Column Name | Description |
| --- | --- |
| CustomerName | The name of the customer |
| TotalOrderAmount | The total amount of all orders placed by the customer |
