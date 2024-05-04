# Coffee Sales Dashboard


## Project Overview
The objective of this project is to examine a coffee sales dataset and produce an interactive dashboard using Excel. The dashboard will provide stakeholders a visualization of key sales metrics offering insights into trends in sales, profit, and product volume, that will support data-driven decision-making.


## Data Source
This project is inspired by [Mo Chen‘s Excel tutorial in Youtube](https://www.youtube.com/watch?v=m13o5aqeCbM&t=1690s) and the dataset is obtained from his [github account](https://github.com/mochen862/excel-project-coffee-sales)
-	coffeeOrdersData.xlxs


## Tools
**Excel** – Data cleaning/transformation, data analysis, dashboard creation


## Data Cleaning/Transformation
To ensure quality and cleaned data, the following tasks were done: 
-	Checking of accuracy and consistency of data format per column
-	Removing of duplicates, if any
-	Checking of null or missing values

All the necessary data used in the analysis were consolidated in the ‘orders’ table using functions such as XLOOKUP, INDEX, and MATCH. Also, additional columns were introduced to determine the day of week of transactions and to calculate total sales, profit and %profit.  



## Data Analysis
The following are the key features of the analysis: 
1.	Sales Overview: Total sales, total profit, and % profit
2.	Regional Insights: Sales data across different locations to understand variations in demand and customer preferences
3.	Time Trends: Sales trends and sales volume over time to identify patterns that may aid in forecasting future sales and the inventory management
4.	Product Analysis: Analyze the performance of individual coffee products, highlighting best-sellers and identifying trends in product popularity


## Results/Findings
1.	**Sales Overview:**
    -	From 2019 to August 2022, the cumulative total of sales amounted to $45,134, with a corresponding profit of $4,520, reflecting a profit margin of 10%. 
    - Total sales remained steady from 2019 to 2020, reaching its peak in 2021.
    - Profit margin remained steady over the years, fluctuating slightly between 9.8% and 10.1%.
2.	**Regional Insights:**
    - The United States consistently contributed the highest share, ranging from 77% to 81%, of total sales.
    - It is followed by Ireland and lastly, by United Kingdom having the least sales.  
3.	**Time Trends:**  
    -	The average monthly sales remained consistent annually, ranging from $1,016 to $1,147 (Note: I excluded here the year 2022 since its data is only up to the month of August).
    -	The months with the highest/lowest sales vary significantly each year.
    -	Likewise, the days of week with the highest/lowest number of orders fluctuates from year to year. 
4.	**Product Analysis:**  
    -	Arabica was the most frequently ordered coffee type based on the cumulative total of orders, whereas Liberica was the least ordered. 
    -	In terms of roast type, Light roast was the most popular, followed by Medium roast, and lastly Dark roast based on the cumulative total of orders. 
    -	However, the most and least ordered coffee types and roast types varied annually. 


## Visualization
Below is the snapshot of the project’s dashboard which is uploaded in this repository. 

![Coffee Sales Dashboard](https://github.com/CharmaineSantiago/coffee-sales-dashboard/assets/158445656/184d568d-a3e9-40ad-858c-6ba0aef0c1d0)


## Recommendations
Here are my high-level recommendations based on the insights discovered:
-	In countries with lower sales performance, develop localized marketing campaigns or product offerings tailored to these country’s preferences. 
-	Also consider implementing seasonal promotions, limited-time offers, or bundling deals to drive incremental sales without compromising profit margins.
-	Ensure continuous and timely monitoring of sales and inventory to discover any pattern in the consumers’ demand per month, per quarter or even per season. 
-	Consider introducing new coffee varieties or roast profiles to align with evolving consumer tastes and capitalize on emerging trends in the coffee market.
-	Conduct regular reviews of sales data to identify opportunities for optimization and areas for improvement in sales strategies and operational efficiency.
