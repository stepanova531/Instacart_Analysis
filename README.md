# Instacart_Analysis
Instacart grocery basket analysis using Python to identify sales patterns as a part of Data Analytics course at CareerFoundry
# Objective
Instacart is an online grocery store that operates through an app. The Instacart stakeholders want to uncover more information about sales patterns to improve thier customer segmentation strategies.
# Data
Data has been taken from Instacart open-source data sets. The customer data set was created the purpose of this analysis.
# Tools
Python,
Jupyter Notebook,
Pandas & NumPy Libraries,
Matplotlib,
Seaborn  
# Insights & Recommendations

[Final report](PK)

The analysis of Instacart data is trying to answer many business questions about how the customers’ ordering behavior differs for different type of clients.      
## What is the distribution among users in regards to their brand loyalty?  How often do they return to Instacart?
The customers are ranked by their loyalty given the number of orders placed:
 Loyal customers: > 40 orders;
 Regular customers: from 10 to 40 orders;
 New customers: < 10 purchases.
- The preferences for when to make the orders are the same. The busiest days are Saturday and Sunday. The busiest hours of the day are from 10 am to 3 pm.
- For the loyal clients who place orders quite often, it will be valuable to save time when they are selecting products. I suggest creating a menu on the app allowing them to save a list of their regular items so that they will be able to add them from their personalized list to the virtual cart on the app.
- For regular customers, I suggest posting personalized ads advertising low prices or sales for the products the client buys regularly.
## What different classifications does the demographic information suggest?  Age?  Income?  Certain types of goods?  Family status?
I analyzed customers’ profile by their age, income, and marital status.
- On the top-10 customers profile by total expenditure, there are mostly customers who have middle- and low-income categories in their profile. We could assume that the high-income customers spend more than other categories because their spending power is higher, however, high-income clients’ share in customer distribution is insignificant at 0.6% and they are not our revenue generated category.
- On the top-10 profile by the average number of orders, there are customers of all age categories and suggested classification by family situation, at the same time these customers have high- or middle income. 
- On the top-10 profiles by the days since prior order are high-income not married clients (including single, divorced or living with parents) 
- On the top-10 profiles by the average spending, there are mostly young people and adults with middle-income profile. Their family situation does not make a significant difference in how much they spend on average.
## Are there certain types of products that are more popular than others?   Which departments have the highest frequency of product orders?
The price frequency shows that the clients purchase the most often the products valued from $1 to $15. 
I suggest the following classification:
High range products: > $15 per item
Mid-range: from $5 to $15 per item
Low range: $5 or less.  
- In list of the most popular products, there are 9 items from Produce department. Another evident trend is that organic food is in high demand with the customers.
- The lists of top-10 departments by the number of orders and revenue generated match except one department. Meat and seafood are in the top list by the revenue, however outside of top-10 by orders placed. Meat and seafood products are ranked as High range. But the customers tend to buy low- and mid- price products.
High range products generate more revenue than other products, however the customers’ orders this category less often.
- I suggest packaging high range products in smaller packs to reduce the price per item. 
- As organic products are very popular, I recommend labeling clearly all the organic products and creating an Organic products category on the app menu.
# Key takeaways
- Deriving new variables, grouping and aggregating functions as well as creating cross tables with Python provide unlimited opportunities for analysis and developing insights. Huge opportunities require constant improvement of coding skills.
- The collection of libraries helps on every stage of data analysis (exploring data, data cleaning, EDA, visualization)  
- Analyzing big data may cause memory issues in RAM. Pandas performance optimization techniques can help avoid running out of memory, e.g. using samplings for exploration, optimizing data type before merging dataframes.
