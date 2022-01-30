# SQL_Project
This repository contains the project for SQL course to obtain the Data Analytics diploma.

## Code Sample
```SQL Server 2014 Management Studio
SELECT c.CompanyName, SUM(soh.TotalDue) AS Total 
FROM SalesLT1.Customer AS c
LEFT JOIN SalesLT.SalesOrderHeader AS soh ON c.CustomerID = soh.CustomerID
GROUP BY c.CompanyName ORDER BY Total DESC
```

## Entity Relationship sample:

<img align="left" alt="JPG" src="https://user-images.githubusercontent.com/98499583/151677075-cf9c5e75-78c1-4113-8861-b49440b98761.JPG" width="40%" height="auto" /> 
