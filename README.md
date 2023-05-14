# Home_Sales

**Project Description**

The following code uses SparkSQL to determine key metrics about home sales data. More specifically, it uses Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

The aim was to answer the following questions:
1. What is the average price for a four-bedroom house sold for each year?
2. What is the average price of a home for each year it was built that has three bedrooms and three bathrooms?
3. What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet?
4. What is the "view" rating for homes costing more than or equal to $350,000?

**Analysis**
1. Prices for four-bedroom houses peaked in 2015, where the average price reached $307,908.86.
2. Prices for 3-BD, 3-BA houses peaked in 2013, where the average price reached $295,962.27.
3. Prices for 3-BD, 3-BA, 2-story, with a lot size of 2,000 or more square feet peaked in 2012, where the average price reached $295,858.68.
4. The average view rating for homes costing more than or equal to $350,000 is 32.26.

**Sources**

UC Berkeley Data Analysis Bootcamp
