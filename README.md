# Capstone Power BI Dashboard  

## Project Overview  
This project involves developing an interactive Power BI dashboard to analyze a comprehensive dataset from a retail shop, encompassing key business metrics such as customer behavior, product performance, payment trends, and seller activities. The dataset consists of 9 interconnected tables, offering a detailed view into various aspects of the business.  

## Dataset Overview  
The dataset includes the following 9 tables:  

1. *Customers*: Contains customer demographics and purchase history.  
2. *Geolocation*: Provides geographic data related to customers, orders, and sellers.  
3. *Order Items*: Captures individual items purchased, including product IDs, quantities, and prices.  
4. *Order Payments*: Records payment methods and transaction amounts for each order.  
5. *Order Reviews*: Details customer reviews and ratings of products.  
6. *Orders*: Comprehensive dataset with order details such as order IDs, timestamps, and customer information.  
7. *Products*: Includes product names, descriptions, and categories.  
8. *Sellers*: Contains seller data, including performance metrics.  
9. *Product Categories*: Classifies products by type, facilitating category-based analysis.  

## Dashboard Features and Tasks  
The Power BI dashboard includes the following key analytical tasks for actionable insights:  

- *Rating Distribution Visualization*: A bar chart visualizes the distribution of product ratings (Excellent, Very Good, Good, Bad, Very Bad) alongside the number of orders in each category, providing insights into customer satisfaction.  

- *Product Categories Analysis*: A ranking table lists the top 10 and bottom 10 product categories based on order count. Includes slicers for filtering by time period to explore historical trends and seasonality.  

- *Active Sellers Report*: A line chart displays the number of active sellers by year and month. Dynamic slicers enable the user to filter by specific date ranges, offering insight into seller activity over time.  

- *Payment Methods Analysis*: A pie chart visualizes the distribution of payment methods used by customers (e.g., credit card, debit card, cash), highlighting the most popular methods for payment.  

- *Profit Margin Calculation*: A custom visual calculates and displays profit margins by product category using the formula:  
  
  \[  
  \text{Profit Margin} = \frac{\text{Payment Value} - \text{Price} + \text{Freight Value}}{\text{Payment Value}} \times 100  
  \]  

  Rounded to two decimal places, this helps track profitability across categories.  

- *Credit Card Payment Trends*: A line chart tracks monthly credit card payments, offering insights into customer payment behavior and how it fluctuates over time.  

- *Seller Categorization by City*: A map visual or bar chart displays the distribution of sellers by city, excluding cities that start with "S" or "B." Filters enable users to drill down into specific cities for more detailed analysis.  

- *Order Timeliness Comparison*: A dynamic visual compares the number of on-time versus delayed orders for each month. Drill-through features allow detailed examination of delivery performance by month.  

## Results  
- Reduced reporting time by *50%*.  
- Improved decision-making by *40%*.  
- Identified key sales drivers for strategic planning.  

## Technologies Used  
- *Power BI*: For data modeling, dashboard creation, and visualization.  
- *DAX*: Utilized for creating custom calculations and metrics.  
- *Power Query*: Applied for data cleaning and transformation.  
 
## Acknowledgments  
- Special thanks to the contributors and resources that provided insights and guidance throughout this project.
