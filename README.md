# Amazon Sales Analysis Project
![Banner Image](https://github.com/Deepakbalachandran/Amazon-Sales-Analysis/blob/main/amazon_india_wide_image-3.jpg)
 
Welcome to the Amazon Sales Analysis project! In this project, we delve into analyzing sales
data from Amazon to extract insights and trends that can help optimize sales strategies,
understand customer behavior, and improve business operations.
## Introduction
This project focuses on analyzing a dataset containing Amazon sales records, including
information such as sales dates, customer details, product categories, and revenue figures. By
leveraging SQL queries and data analysis techniques, we aim to answer various questions and
uncover valuable insights from the dataset.
## Dataset Overview
The dataset used in this project consists of 10000 rows of data, representing Amazon
sales transactions. Along with the sales data, the dataset includes information about customers,
products, orders, and returns. Before analysis, the dataset underwent preprocessing to handle
missing values and ensure data quality.
## Analysis Questions Resolved
During the analysis, the following key questions were addressed using SQL queries and data
analysis techniques:

1. Show the customer names,customer_ID,Product name,and total number of returns & also show the customer when the number of returns>2 as "High rx" and rest as "Low rx"?
   
![Returning customer query](https://github.com/Deepakbalachandran/Amazon-Sales-Analysis/blob/main/Q1.jpg)

2. Write a sql query to find the 2nd highest sales per state and show the product name and seller from where it is sold?

![Returning customer query](https://github.com/Deepakbalachandran/Amazon-Sales-Analysis/blob/main/Q5.jpg)

3. Find out the top 5 customers who made the highest profits?

![Returning customer query](https://github.com/Deepakbalachandran/Amazon-Sales-Analysis/blob/main/Q3.jpg)

4. Write a query and return the the top 5 product names were the growth rate decreased by previous years by sales, show the product product_id,product name,years,growth_rate decreased?

![Returning customer query](https://github.com/Deepakbalachandran/Amazon-Sales-Analysis/blob/main/Q4.jpg)

5. Identify the top 6 states with the highest total orders, where each state's total orders exceed the average order across all states. Return the state name and the total number of orders for each?

![Returning customer query](https://github.com/Deepakbalachandran/Amazon-Sales-Analysis/blob/main/Q6.jpg)

6. Create a store procedure to take the input order_id & Order_date from the user and display the order_id,customer_id,customer_name & order_date, and also provide the errror message if the order ID or date is wrong

![Returning customer query](https://github.com/Deepakbalachandran/Amazon-Sales-Analysis/blob/main/Q7.jpg)


## Entity-Relationship Diagram (ERD)

![Returning customer query](https://github.com/Deepakbalachandran/Amazon-Sales-Analysis/blob/main/ERD.jpg)

An Entity-Relationship Diagram (ERD) has been created to visualize the relationships between the tables in the dataset. This diagram provides a clear understanding of the data structure and helps in identifying key entities and their attributes

## Getting Started
To replicate the analysis or explore the dataset further, follow these steps
1.Clone the repository to your local machine.
2.Ensure you have a SQL environment set up to execute queries.
3.Load the provided dataset into your SQL database.
4.Execute the SQL queries provided in the repository to analyze the data and derive insights.
5.Customize the analysis or queries as needed for your specific objectives.

## Conclusion
Through this project, we aim to provide valuable insights into Amazon sales trends, customer preferences, and other factors influencing e-commerce operations. By analyzing the dataset and addressing the key questions, we hope to assist stakeholders in making informed decisions and optimizing their sales strategies.

Feel free to explore the repository and contribute to further analysis or enhancements!

## Notice:
All customer names and data used in this project are computer-generated using AI and random functions. They do not represent real data associated with Amazon or any other entity. This project is solely for learning and educational purposes, and any resemblance to actual persons, businesses, or events is purely coincidental
