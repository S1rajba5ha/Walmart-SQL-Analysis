# Walmart-SQL-Analysis

## About
### About
This project aims to explore the Walmart Sales data to understand top performing branches and products, sales trend of of different products, customer behaviour. The aims is to study how sales strategies can be improved and optimized.

# Purposes Of The Project
The major aim of thie project is to gain insight into the sales data of Walmart to understand the different factors that affect sales of the different branches.

# Exsisting Data
| Column                  | Description                             | Data Type      |
| :---------------------- | :-------------------------------------- | :------------- |
| invoice_id              | Invoice of the sales made               | VARCHAR    |
| branch                  | Branch at which sales were made         | VARCHAR     |
| city                    | The location of the branch              | VARCHAR    |
| customer_type           | The type of the customer                | VARCHAR    |
| gender                  | Gender of the customer making purchase  | VARCHAR    |
| product_line            | Product line of the product solf        | VARCHAR   |
| unit_price              | The price of each product               | DECIMAL |
| quantity                | The amount of the product sold          | INT            |
| VAT                     | The amount of tax on the purchase       | DECIMAL    |
| total                   | The total cost of the purchase          | DECIMAL |
| date                    | The date on which the purchase was made | DATE           |
| time                    | The time at which the purchase was made | TIME      |
| payment_method          | The total amount paid                   | DECIMAL |
| cogs                    | Cost Of Goods sold                      | DECIMAL |
| gross_margin_percentage | Gross margin percentage                 | DECIMAL   |
| gross_income            | Gross Income                            | DECIMAL |
| rating                  | Rating                                  | DECIMAL    |

# Newly added columns
| Column                  | Description                             | Data Type      |
| :---------------------- | :-------------------------------------- | :------------- |
| time_of_day             | it is to categorise the time of day     | VARCHAR    |
| month_name              | The month at which the purchase was made| VARCHAR     |
| date_name               | it determines the week name of purchase | VARCHAR    |

# Analysis List

1. Product Analysis
> Conduct analysis on the data to understand the different product lines, the products lines performing best and the product lines that need to be improved.

2. Sales Analysis
> This analysis aims to answer the question of the sales trends of product. The result of this can help use measure the effectiveness of each sales strategy the 
   business applies and what modificatoins are needed to gain more sales.

3. Customer Analysis
> This analysis aims to uncover the different customers segments, purchase trends and the profitability of each customer segment.
   
## Questions for Analysis

# Product Analysis
1. How many unique cities does the data have and their count?
2. How many unique product lines does the data have?
3. What is the most selling product line ?
4. What is the most common payment method?    
5. What is the total revenue by month?  
6. What month had the largest COGS?
7. What product line had the largest revenue?
8. What is the city with the largest revenue?
9. What product line had the largest VAT?
10. Fetch each product line and add a column to those product line showing "Good", "Bad". Good if its greater than average sales?
11. Which branch sold more products than average product sold?
12. What is the most common product line by gender?
13. What is the average rating of each product line ?

# Customer Analysis
1. How many unique customer types does the data have?   
2. How many unique payment methods does the data have?   
3. What is the most common customer type?
4. Which customer type buys the most?    
5. What is the gender of most of the customers?
6. What is the gender distribution per branch?
7. Which time of the day do customers give most ratings per branch?
8. Which day of the week has the best avg ratings?
9. Which day of the week has the best average ratings per branch?

# Sales Analysis
1. Number of sales made in each time of the day per weekday?   
2. What is the revenue generated by customer?
3. Which city has the largest tax/VAT percent?   
4. Which customer type pays the most in VAT?










   
   
   
