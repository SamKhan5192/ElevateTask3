# ElevateTask3
## *📊 Sales Dashboard Project*
# Objective
Design an interactive dashboard for business stakeholders using **Power BI** to provide insights into sales performance, trends, and key metrics.

# Dataset Overview
**File**: `Sales Dataset.csv`  
**Records**: ~2,500+ rows 
# *Columns*

Here is a detailed column description for your Sales Dataset:
Column Name	Description<br>
Order ID	Unique identifier for each customer order or transaction.<br>
Amount	Total monetary value of the order (revenue).<br>
Profit	Net profit earned from the order (Amount - Cost).<br>
Quantity	Number of items or units sold in the order.<br>
Category	High-level classification of products (e.g., Electronics, Clothing, Home).<br>
Sub-Category	More detailed classification within a category (e.g., Mobile, Laptop under Electronics).<br>
PaymentMode	Payment method used by the customer (e.g., Credit Card, UPI, Cash).<br>
Order Date	The exact date on which the order was placed. (Should be converted to datetime for analysis)<br>
CustomerName	Name of the customer placing the order. (Useful for CRM or loyalty insights)<br>
State	Indian state where the order was delivered or billed.<br>
City	City within the state for delivery or billing.<br>
Year-Month	Aggregated time format (YYYY-MM) used for monthly trend analysis. (Derived from Order Date)<br>

# Dashboard Features

- **KPI Cards**: Total Sales, Total Profit, Growth %, Profit Margin %  
- **Time-Series Analysis**: Line chart of monthly sales  
- **Sales Breakdown**:
  - Bar chart: Top 10 Customer by Sales 
- **Filters / Slicers**: City, Category, PaymentMode 
- **Geographical** Profit by City and Category 
