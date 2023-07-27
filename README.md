# Big-Data-Challenge

In this challenge, we use SparkSQL to determine key metrics about home sales data. 
Then we use Spark to create temporary views, partition the data, cache and uncache a temporary table, 
and verify that the table has been uncached.

We seek to answer the following questions:

What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

+----+---------+
|YEAR|AVG_PRICE|
+----+---------+
|2022|296363.88|
|2021|301819.44|
|2020|298353.78|
|2019| 300263.7|
+----+---------+

What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? 
Round off your answer to two decimal places.

What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
