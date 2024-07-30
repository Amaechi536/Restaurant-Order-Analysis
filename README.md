# Restaurant Order Analysis


## Project Overview
### Maven Roasters, quarter's worth of orders from a fictitious restaurant serving international cuisine, including the date and time of each order, the items ordered, and additional details on the type, name and price of the items.

## Project Scope
### This project involves thorough analysis of maven roasters order data, comprises key elements such as category, item name, and detailed order information. the analytical scope spans historical data from July 14, 2024  to July 27,2024, providing a comprehensive view of maven roasters operational performance during this time. The analysis helps in understanding of the restaurant order sales parttern and development within the specified period.
## Business Objective
### The comprehensive goals of this analysis is to provide a refined understanding of maven roasters order sales performance, the idea covers changes in maven roasters order sales over a specific timeframe, discerning the certain times with more or less order, cuisines which should be focused on developing more menu items for based on the data. Through a comprehensive exploration of these  aspect , the analysis aspires to furnish actionable insights that can inform strategic decisions and optimize maven roasters overall operational capability.
## Document Purpose
### This document helps to provide insights into the project’s data source, data analysis, visualizations and other relevant information.
## Data source
### This project uses a dataset, sourced from [Maven Analytics](https://mavenanalytics.io/data-playground?order=date_added%2Cdesc&page=4) Website, made specifically for practice purposes. the dataset, presented in the form of excel file, a single table with 122,34 rows and 10 columns, the dataset contains unique columns for a comprehensive analysis, which involves order details, order-id, order time, item, item name, category, price, quantity, and total.
## Data Cleaning and Processing
### Having clean data facilitates a smoother analytics process, enabling researchers, analysts, and decision makers to draw meaningful conclusions and make informed decisions based on trustworthy information. 
## Added New Columns
### New columns, namely quantity and price, these additional columns play a pivotal role in the analysis, by facilitating an exploration of how maven roaster’s sales have changed over time.
## Data Analysis and Insight
### the analysis helps to identify least and most ordered items and the category they were in. what highest spent order look like, item bought and how much spent. certain times with more or less orders. Cuisines that should focus on developing more menu items for base on the data,this analysis provides insight addressing the following questions.
## 1.what where the least and most ordered items? what categories where they in?
### The question from maven roasters, restaurant order, seeks to understand the least and most ordered item and what category they belong, to address this question in Microsoft excel, pivot table was created, adding item-name and category on  rows then on values order-id was added. This gives result of least and most ordered item and what category they belong, sort by ascending order.
![](https://github.com/Amaechi536/Restaurant-Order-Analysis/blob/main/Screenshot%202024-07-28%20164448.png)
## 2.what do the highest order look like? which item did they buy and how much did they spend?
### To provide answer to this quantity column was created using =COUNTIFS($B$2:$B$12235,B2,$F$2:$F$12235,F2) selecting the order-id and item-name and adding absolute reference.  And also create the total column by sum(price*quantity).
### To provide accurate answer, order id was inserted under rows in pivot then below comes the item name on the value sum of total was placed. Sort by descending order.  This helps to analyze the highest spent orders alongside with the items bought and total amount spent.
![](https://github.com/Amaechi536/Restaurant-Order-Analysis/blob/main/Screenshot%202024-07-28%20164900.png)
## 3.Were there certain times that had more or less orders?
### Using pivot table order date is being placed on rows and order id on values by doing this march has more orders and January has less orders, sort DESC.
![](https://github.com/Amaechi536/Restaurant-Order-Analysis/blob/main/Screenshot%202024-07-28%20203511.png)
## 4.Which cuisines should we focus on developing more menu items for based on the data?
### To provide answer to this using the pivot table, category placed on the rows while quantity on values and total below quantity on value. sort DESC.
![](https://github.com/Amaechi536/Restaurant-Order-Analysis/blob/main/Screenshot%202024-07-28%20164725.png)






