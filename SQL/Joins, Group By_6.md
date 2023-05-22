# **Q38 - SQL Coding Question**

## **Schema**

Table 1: Sales

| Column Name | Data Type |
| --- | --- |
| SaleID | int |
| ProductID | int |
| SaleDate | date |
| Quantity | int |
| Price | float |

Table 2: Products

| Column Name | Data Type |
| --- | --- |
| ProductID | int |
| ProductName | varchar |
| SupplierID | int |
| CategoryID | int |
| UnitPrice | float |

Table 3: Categories

| Column Name | Data Type |
| --- | --- |
| CategoryID | int |
| CategoryName | varchar |
| Description | varchar |

## **Query**

Write a SQL query to retrieve the name of the category with the highest total quantity sold. The output should have the following columns:
| Column Name | Description |
| --- | --- |
| CategoryName | The name of the category |
| TotalQuantity | The total quantity sold for all products in the category |
