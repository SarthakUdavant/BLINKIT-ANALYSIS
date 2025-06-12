# BLINKIT-ANALYSIS
## Description

This project involves exploratory data analysis (EDA) on Blinkit (formerly Grofers) product data to uncover key insights related to product pricing, discounts, categories, ratings, and availability. The analysis uses Python libraries such as pandas, matplotlib, and seaborn to visualize trends, compare product segments, and identify consumer-focused strategies.

## Overview 

🔍 Key Areas of Analysis:

1.Top-Selling Products:
- Identifying items with the highest sales volume.
- Useful for inventory planning and promotions
  
2.Time-Based Trends:
- Analyzing sales by day of the week and time of day.
- Helps understand peak ordering hours and plan logistics.
  
3.Revenue by Category:
- Measuring income generated per product category.
- Assists in identifying profitable product lines.
  
4.Customer Buying Patterns:
- Exploring frequent buyers and product preferences.
- Supports targeted marketing and personalized offers.
  
5.High-Demand Locations:
- Mapping orders by delivery zones or areas.
- Useful for planning delivery routes and resource allocation.
  
6.Repeat Orders & Retention:
- Identifying returning customers.
- Indicates customer satisfaction and loyalty.

 ## ✅ Project Objectives:
 - Analyze the Blinkit product dataset to understand sales performance, item characteristics, and outlet attributes.
 - Identify key insights about item types, visibility, outlet types, and other factors influencing sales.

## 🛠️ Tools & Technologies Used:
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook for analysis and visualization
- Data Cleaning & Preparation to handle missing values and outliers
- Exploratory Data Analysis (EDA) to draw meaningful patterns

## 📈 🔍 Final Insights:

1.Total Sales by Item Type:

 - Certain item types like Fruits and Vegetables, Frozen Foods, and Canned goods had noticeably higher total sales.
 - These categories are likely core contributors to revenue and should be prioritized in promotions or restocking strategies.
   
2.Fat Content by Outlet for Total Sales:

 - Low Fat and Regular item variants showed variation in performance across different outlets.
 - Standardizing labeling (e.g., combining “Low Fat” and “low fat”) is essential for clean analysis.
 - Some outlets may favor certain fat content categories—useful for localized marketing.
   
3.Sales by Outlet Size:

 - Medium-sized outlets generally report higher sales than small or high sized ones.
 - This suggests an operational sweet spot in terms of space, staffing, or product range.
   
4.Sales by Outlet Location Type:

 - Tier 1 and Tier 2 cities perform better than Tier 3, reflecting purchasing power and demand in urban and semi-urban markets.
Products with low turnover.

## 📌 Key Results:

1.Dataset Size:
 - Total records: 8,523
 - Total features (columns): 12

2.Attributes Analyzed:
 - Product features like Item Type, Item Fat Content, Item Weight, Item Visibility
 - Outlet attributes such as Outlet Type, Outlet Size, Location Type, and Establishment Year
 - Target variable: Sales

3.Data Observations:
 - Some missing values found in Item Weight.
 - Categories like Item Fat Content include variants such as "Low Fat", "low fat", and "Regular" — may require normalization.

4.Sales Trends:
 - Sales vary significantly by Outlet Type and Item Type.
 - Outlets with larger size and established earlier tend to show more stable or higher sales.
 - Visibility and rating may correlate with sales performance.

5.Top Item Categories:
 - Fruits and Vegetables, Snack Foods, and Dairy appeared frequently.
 - Soft drinks and canned goods also contributed notably.
