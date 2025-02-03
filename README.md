# MADHAV-STORE-DASHBOARD

# Overview

This project involves creating an interactive and visually appealing sales dashboard for an e-commerce business using Microsoft Power BI. The dashboard provides insights into various sales metrics, including total revenue, profit, average order value (AOV), and quantity sold, while segmenting data across multiple dimensions such as states, customer names, product categories, and payment methods.

The goal of the dashboard is to empower stakeholders with actionable insights for informed decision-making.

# Features of the Dashboard

#Key Metrics Overview
  Total Amount (Revenue): ₹438K
  Total Quantity Sold: 5615
  Total Profit: ₹37K
  Average Order Value (AOV): ₹121K

#Data Segmentation
  Sum of Amount by State: Highlights the revenue contribution from states like     
  Maharashtra, Madhya Pradesh, Uttar Pradesh, and Delhi.
  Sum of Amount by Customer Name: Displays the top customers based on revenue.
  Sum of Quantity by Category: Breaks down sales by categories: Clothing (63%), 
  Electronics (21%), and Furniture (17%).
  Sum of Quantity by Payment Mode: Shows payment preferences like Cash on Delivery 
  (43.74%), UPI (20.61%), Debit Card (13.2%), and Credit Card (11.97%).

#Trends and Insights

  Profit by Month: A line chart displaying monthly profits and losses.
  Profit by Sub-Category: A bar chart showing profits across sub-categories like 
  Printers, Bookcases, and Sarees.
  
#Interactive Elements

  Filters for Quarter and State to customize the view.
  Dynamic visuals that adjust based on user selections.

# Datasets Used

1. Orders.csv
Purpose: Provides transactional-level details, including order IDs, product IDs, customer names, sales amount, and payment methods.
Columns:
Order ID
Customer Name
Sales Amount
Payment Method
State
Category

2. Details.csv
Purpose: Contains detailed information on products, categories, sub-categories, and quantities sold.
Columns:
Product ID
Category
Sub-Category
Quantity Sold
Profit

# Steps to Recreate the Dashboard

Data Loading

Import Orders.csv and Details.csv into Power BI.
Ensure proper relationships are established between the datasets.

Data Transformation

Clean the data to remove inconsistencies and null values.
Use Power Query to standardize columns and formats.

Measure Creation

Create calculated measures for metrics like Total Revenue, Total Profit, and Average Order Value.

Visualizations

Use bar charts, pie charts, and line graphs for effective data representation.
Add slicers for interactivity (e.g., State and Quarter filters).

Styling and Layout

Apply a dark-themed background for a modern look.
Use consistent color schemes for categories and metrics.

# Insights Derived

Top Performing States: Maharashtra and Madhya Pradesh contribute significantly to total revenue.

Customer Focus: Key customers like Harivansh drive the majority of sales.

Category Trends: Clothing dominates sales quantity, while Electronics has a smaller share.

Payment Trends: COD remains the most preferred mode of payment.

Seasonality: Profits peak in November, indicating potential seasonal demand.

# Tools and Technologies Used

Microsoft Power BI Desktop
Power Query
DAX (Data Analysis Expressions)

# Future Improvements
Incorporate real-time data streaming for up-to-date insights.
Add predictive analytics to forecast future sales trends.
Include customer demographics for a deeper understanding of the target audience.
Create mobile-friendly views for on-the-go accessibility.

<img width="1440" alt="Screenshot 2025-02-03 at 10 52 10 PM" src="https://github.com/user-attachments/assets/9d473682-e327-4cf7-bcd0-65e1ee851058" />
