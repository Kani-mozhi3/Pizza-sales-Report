

## 🍕 Pizza Sales Analysis Project
  This project provides a comprehensive end-to-end data analytics solution, transforming raw pizza sales data into actionable business insights. The process involves data cleaning, SQL-based analysis, and dynamic visualization using Power BI to track key performance indicators (KPIs) and sales trends.

## 🚀 Project Overview
   The goal of this project is to analyze a year's worth of pizza sales data to identify top-performing products, seasonal sales patterns, and customer purchasing habits. This helps business owners optimize their menu and improve operational efficiency.

## 🛠️ Tools Used
Data Source: CSV/Excel Dataset

Database: MS SQL Server (for data querying and KPI calculation)

Visualization: Power BI (for dashboarding and storytelling)

Process: ETL (Extract, Transform, Load)

## 🧹 Data Cleaning & Transformation
 - Before analysis, the raw data underwent several preprocessing steps to ensure accuracy:

 - Checked for missing values and null entries.

 - Standardized date and time formats for time-series analysis.

 - Created new calculated columns (e.g., Total Price per order) to facilitate deeper analysis.

 - Ensured data types were consistent across the SQL database.

## 🗄️ SQL Analysis
The following SQL queries were executed to extract high-level KPIs and detailed sales metrics:

 - Total Revenue: Sum of the total price of all orders.

 - Average Order Value: Total Revenue divided by the number of orders.

 - Best/Worst Sellers: Ranked pizzas by revenue, quantity, and total orders.

 - Sales Trends: Analysis by days of the week and monthly patterns.

## 📊 Power BI Dashboard
 The Power BI dashboard connects directly to SQL Server and visualizes the main KPIs.

 ### Key features:
  
 - KPI cards: total revenue, total orders, total pizzas sold, average order value, and average pizzas per order.

  ### Trend charts:

  - Daily trend of total orders by weekday.
​​

 ### Distribution visuals:

  - Total orders by pizza category (classic, supreme, veggie, chicken, etc.).
​

  - Total orders by pizza size (small to xx-large).


    <img width="1009" height="581" alt="Report" src="https://github.com/user-attachments/assets/72a2bea9-8a84-4f68-872b-066d1a70cf4a" />



## 🚀 How to Run
 - Import the pizza sales CSV files into SQL Server tables.
​

 - Run the SQL cleaning and analysis scripts to prepare the final views.
​

 - Open the Power BI file and update the SQL Server connection settings.

 - Refresh the data to load the latest results into the dashboard  
​

## 🏆 Top & Bottom Performers
The dashboard identifies the highest and lowest performing products to help with menu optimization and inventory planning.

### 🔥 Top 5 Best Sellers
By Revenue: The Thai Chicken Pizza leads with the highest contribution to total sales.

By Quantity: The Classic Deluxe Pizza is the most frequently sold item.

By Total Orders: The Classic Deluxe Pizza also appears in the highest number of unique transactions.

### ❄️ Bottom 5 Worst Sellers
By Revenue: The Brie Carre Pizza generates the least revenue for the store.

By Quantity: The Brie Carre Pizza has the lowest sales volume.

By Total Orders: The Brie Carre Pizza is the least included item in customer orders.


<img width="1022" height="587" alt="Top-bottom" src="https://github.com/user-attachments/assets/6c55f756-59d5-45bc-91d6-01a2f1a9763b" />

