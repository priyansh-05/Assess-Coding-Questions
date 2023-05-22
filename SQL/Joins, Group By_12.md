# **Q32 - SQL Coding Question**

## **Schema**

Table 1: Books

| Column Name | Data Type |
| --- | --- |
| BookID | int |
| Title | varchar |
| AuthorID | int |
| PublisherID | int |
| PublicationDate | date |
| Price | float |

Table 2: Publishers

| Column Name | Data Type |
| --- | --- |
| PublisherID | int |
| PublisherName | varchar |
| Address | varchar |
| Phone | varchar |
| Email | varchar |

## **Query**

Write a SQL query to retrieve the name of the publisher with the highest total revenue. The output should have the following columns:

| Column Name | Description |
| --- | --- |
| PublisherName | The name of the publisher |
| TotalRevenue | The total revenue generated by the publisher |