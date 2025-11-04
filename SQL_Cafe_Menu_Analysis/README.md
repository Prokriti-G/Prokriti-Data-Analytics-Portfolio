# Café Menu Analysis (SQL Project)

## Objective
Analyze the café’s new menu to identify which items are performing well, which are underperforming, and what the top customers prefer. The goal is to provide actionable insights for menu planning and customer engagement.

## Dataset
- Source: [Maven Analytics](https://app.mavenanalytics.io/guided-projects/d7167b45-6317-49c9-b2bb-42e2a9e9c0bc#dataset)

## Process
1. Explored `menu_table` to understand the new menu items and categories.  
2. Explored `order_details` to see which items were ordered most frequently.  
3. Used JOINs to combine the tables for a complete view of customer purchases.  
4. Applied aggregate functions (`COUNT`, `SUM`) and `GROUP BY` to summarize orders and revenue.  
5. Identified top customers by frequency and spending.

## Key Insights
- The most ordered item is a Hamburger and the least ordered item is Chicken Tacos.  
- The most expensive item on the menu is Shrimp Scampi and the least expensivve item is Edamame. 
- The most expensive category is Italian and the least expensive category is American
- The top five highest spend orders are ordering more Italian food than any other category.  

 ## Next steps: 
 With more detailed or larger datasets, further insights could include seasonal trends or item combinations that drive sales.

## SQL Skills Demonstrated
- SELECT queries with filtering  
- GROUP BY and aggregate functions (`COUNT`, `SUM`)  
- JOINs to combine tables  
- Ranking items by popularity  
- Customer segmentation  
- Calculating revenue by item or category

## Files Included
- [`cafe_analysis.sql`](./SQL_Cafe_Menu_Analysis/cafe_analysis.sql)  
- Screenshots of query results

## Notes
This project demonstrates how SQL can be used to explore customer and sales data, summarize results, and provide actionable insights for menu planning and customer engagement.

