Create a medallion architecture in a Microsoft Fabric lakehouse
In this exercise you will build out a medallion architecture in a Fabric lakehouse using notebooks. You will create a workspace, create a lakehouse, upload data to the bronze layer, transform the data and load it to the silver Delta table, transform the data further and load it to the gold Delta tables, and then explore the semantic model and create relationships.

In this Hand - on you'll be experiencing the following things


1. Create a workspace
2. Create a lakehouse and upload data to bronze layer
3. Transform data and load to silver Delta table
4. Explore data in the silver layer using the SQL endpoint
5. Transform data for gold layer
6. (OPTIONAL) Create a semantic model


- Query to calculate the total sales for each year in the sales_silver table.


SELECT YEAR(OrderDate) AS Year
    , CAST (SUM(Quantity * (UnitPrice + Tax)) AS DECIMAL(12, 2)) AS TotalSales
FROM dbo.sales_silver
GROUP BY YEAR(OrderDate) 
ORDER BY YEAR(OrderDate)


- Query to calculate the total quantity of items purchased by each customer in the sales_silver table and returns the top 10 customers by quantity purchased


 SELECT TOP (10) CustomerName, SUM(Quantity) AS TotalQuantity
 FROM dbo.sales_silver
 GROUP BY CustomerName
 ORDER BY TotalQuantity DESC