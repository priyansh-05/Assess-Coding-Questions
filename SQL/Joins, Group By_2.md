# Q2 - SQL Coding Question

## Schema

Table 1: Products

| Column Name | Data Type |
| --- | --- |
| ProductID | int |
| ProductName | varchar |
| SupplierID | int |
| CategoryID | int |
| Price | float |

Table 2: Categories

| Column Name | Data Type |
| --- | --- |
| CategoryID | int |
| CategoryName | varchar |
| Description | varchar |

## Query

Write a SQL query to retrieve the total number of products in each category. The output should have the following columns:

| Column Name | Description |
| --- | --- |
| CategoryID | The ID of the category |
| CategoryName | The name of the category |
| TotalProducts | The total number of products in the category |

The query should return the results in descending order of the TotalProducts column.
