# ADIDAS 2021-SALES-PROJECT
The Adidas sales dataset is a collection of data that includes information on the sales of Adidas products. The dataset includes details such as the number of units sold, the total sales revenue, the location of the sales, the type of product sold, and any other relevant information.

Each row represents an Invoice for a unique Retailer. The columns in the dataset are as follows:   
Retailer,	Retailer ID,	Invoice, Date,	Region,	State	,City,	Product,	Price per Unit,	Units Sold,	Total Sales,	Operating Profit,	Operating Margin,	Sales Method.
  
## Data Cleaning
There were no null values, however most of the Numeric data needed for analysis were formated as Strings. These Columns were converted to the proper data type.  
I selected only data for the year 2021 for my analysis. 
## EDA
I was able to perform the eploratory data analysis on the data using the .describe() function.

## VISUALIZATION and INSIGHTS
* Visual of the sales trend in year 2021: sales appear to trend downwards from the beginning of the year to the end.
* Visual of the sales trend by month in 2021 showing month with highest and lowest sale :
   Sales increased slightly from the beginning of the year to March where its the lowest. July, August and December hold the highest sales
* Correlation between price of a product and Number of products sold : The scatter plot shows a positive correlation between price and
  number of products sold. This means that as the price of the product increases, the number of products sold also tends to increase.
* AVERAGE operating margin by retailer and Product: The average operating margin for apparel is higher than the average operating margin for footwear across all retailers.
  Amazon has the highest average operating margin for both men's and women's apparel while Sports Direct has the Lowest.
  Foot Locker has the highest average operating margin for both men's athletic footwear and men's street footwear.
* Bar Plot showing Operating Profit per State: There is a large disparity in operating profit between different states.
  South Carolina has the highest while RHODE island has the smallest Operating PROFIT
* Pie chart showing the percentage of unit sold per product type: Men’s street footwear is the most popular category while Men’s apparel is the least popular category.
* Distribution of Sales by Region highlighting the sales method: Online sales appear to be the most frequent method across all regions.

