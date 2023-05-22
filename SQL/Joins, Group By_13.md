# **Q31 - SQL Coding Question**

## **Schema**

Table 1: Movies

| Column Name | Data Type |
| --- | --- |
| MovieID | int |
| Title | varchar |
| Director | varchar |
| GenreID | int |
| ReleaseDate | date |
| Rating | float |

Table 2: Genres

| Column Name | Data Type |
| --- | --- |
| GenreID | int |
| GenreName | varchar |

## **Query**

Write a SQL query to retrieve the name of the genre with the highest average rating. The output should have the following columns:

| Column Name | Description |
| --- | --- |
| GenreName | The name of the genre |
| AvgRating | The average rating of all movies in the genre |
