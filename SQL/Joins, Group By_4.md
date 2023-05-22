# **Q40 - SQL Coding Question**

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

Table 3: OrderItems

| Column Name | Data Type |
| --- | --- |
| OrderItemID | int |
| OrderID | int |
| ProductID | int |
| Quantity | int |
| Price | float |

Table 4: Products

| Column Name | Data Type |
| --- | --- |
| ProductID | int |
| ProductName | varchar |
| SupplierID | int |
| CategoryID | int |
| UnitPrice | float |

Table 5: Categories

| Column Name | Data Type |
| --- | --- |
| CategoryID | int |
| CategoryName | varchar |
| Description | varchar |

## **Query**

Write a SQL query to retrieve the name of the customer who has purchased the highest total quantity of products. The output should have the following columns:

| Column Name | Description |
| --- | --- |
| CustomerName | The name of the customer |
| TotalQuantity | The total quantity of products purchased by the customer |
