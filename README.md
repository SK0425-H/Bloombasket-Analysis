# Bloombasket Sales #
### Problem Statement ###
A Bloombasket Sales company has the sales for the last 3 years and they want to analyze it now. There is a Dimension Data where there is a list of companies and their line of business. There are 3 years of sales data. There is also a Target Data. 
### Data Set ###
The data set is - https://drive.google.com/drive/folders/1IuZyEBrR2s64N0mlynwLZKLcWTIK CIvP?usp=sharing
### Data Transformation ###
The dataset consists of five tables: a Dimension table, Sales tables for 2017, 2018, and 2019 respectively, and a Target table. Each Sales data table for a specific year includes columns such as issue date, salesperson ID, customer ID, and total sales. The Target table records the total sales provided by each salesperson. 
The Dimension table encompasses information regarding salespersons, customers, dates, cities, and more. The Excel sheets are imported into Power BI, where the data types of all columns are verified and any errors or null values are removed. This process is repeated for each Excel sheet, followed by importing the data and creating a dashboard
### Data Model ###
In Power BI, there exists a many-to-many relationship between the Dimension table and each year's Sales table. The Salesperson table holds detailed information about salespersons. Meanwhile, the Target data establishes a one-to-many relationship with the Sales table.
### Insights ###
-In 2017, the total sales amounted to $6.65 million, in 2018 it was $10.21 million, and in 2019 it reached $1.05 million, resulting in a cumulative total sales of $17.91 million.

-The total number of transactions placed is 26k.

-The total number of customers is 2,811.

-The highest sales were made in October, followed by September and November.

-The lowest sales were made in February followed by March and April.

-Actual sale is 17.91M where target sale is 23.83M.

-Badger City has the maximum number of customers.

-Sweets and wheat flour had higher sales in 2017, and Wheat flour and yeast had higher sales in 2018.

### Conclusion ###
The logistics dashboard has been developed, showcasing a range
 of Key Performance Indicators (KPIs). 
The report includes visualizations that offer a comprehensive analysis of the provided data,
 presenting various metrics for deeper insights.



