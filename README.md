# Home_Sales

In this challenge, SparkSQL was used to determine key metrics about home sales data. Then Spark was used to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

Instructions

Install PySpark and import PySpark SQL functions for this assignment provided by the template.

![PySpark Ins](https://github.com/user-attachments/assets/7d696391-848d-4c30-aff6-10adb7f9e098)

![PySpark SQL](https://github.com/user-attachments/assets/93d6ec30-6fa4-4c81-b37a-fc1e9910caec)

Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.

Create a temporary table called home_sales.

Answer the following questions using SparkSQL:
What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

![alt text](avg_price_4br.png)

What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

![alt text](avg_price_3berm_3barm.png)

What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

![alt text](avg_price_3_berm_3_barm_2_fl.png)

What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

![alt text](avg_price.png)

Cache your temporary table home_sales.

Check if your temporary table is cached.

Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

Partition by the "date_built" field on the formatted parquet home sales data.

Create a temporary table for the parquet data.

Run the query that filters the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

Uncache the home_sales temporary table.

Verify that the home_sales temporary table is uncached using PySpark.

The file of Home_Sales_colab.ipynb is shared through the link below:
https://colab.research.google.com/drive/1zpycQIvUxUmqVig2E_0U1S2x6V19xr5e?usp=sharing
