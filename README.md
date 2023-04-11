# Home_Sales
Module 22 Challenge

In this challenge, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

## Procedure:
* Rename the Home_Sales_starter_code.ipynb file as Home_Sales.ipynb.

* Import the necessary PySpark SQL functions for this assignment.

* Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.

* Create a temporary table called home_sales.

* Answer Questions

* Cache your temporary table home_sales.

* Check if your temporary table is cached.

* Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

* Partition by the "date_built" field on the formatted parquet home sales data.

* Create a temporary table for the parquet data.

* Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

* Uncache the home_sales temporary table.

* Verify that the home_sales temporary table is uncached using PySpark.

* Download your Home_Sales.ipynb file and upload it into your "Home_Sales" GitHub repository.

## QUESTIONS:
1. What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
![Screen Shot 2023-04-11 at 9 01 49 AM](https://user-images.githubusercontent.com/111457464/231187785-0cd5867c-271b-4407-9133-5f311e3b8bb3.png)

2. What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
![Screen Shot 2023-04-11 at 9 02 32 AM](https://user-images.githubusercontent.com/111457464/231187921-809d761b-bb80-4414-9f34-1859f2db7ec3.png)

3. What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
![Screen Shot 2023-04-11 at 9 02 58 AM](https://user-images.githubusercontent.com/111457464/231188027-107737be-6d1c-48c2-b4b4-e213b8560c75.png)

4. What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
  32.26 Views
