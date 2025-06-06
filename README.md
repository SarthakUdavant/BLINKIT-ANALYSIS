# BLINKIT-ANALYSIS

This project involves exploratory data analysis (EDA) on Blinkit (formerly Grofers) product data to uncover key insights related to product pricing, discounts, categories, ratings, and availability. The analysis uses Python libraries such as pandas, matplotlib, and seaborn to visualize trends, compare product segments, and identify consumer-focused strategies.

✅ Project Objectives:
 - Analyze the Blinkit product dataset to understand sales performance, item characteristics, and outlet attributes.
 - Identify key insights about item types, visibility, outlet types, and other factors influencing sales.

📌 Key Results:
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

📈 🔍  Insights:
1.Total Sales by Item Type:

 - Certain item types like Fruits and Vegetables, Frozen Foods, and Canned goods had noticeably higher total sales.
 - These categories are likely core contributors to revenue and should be prioritized in promotions or restocking strategies.
   
2.Fat Content by Outlet for Total Sales:

 - Low Fat and Regular item variants showed variation in performance across different outlets.
 - Standardizing labeling (e.g., combining “Low Fat” and “low fat”) is essential for clean analysis.
 - Some outlets may favor certain fat content categories—useful for localized marketing.
   
3.Sales by Outlet Establishment Year:

 - Outlets established earlier (2000–2010) tend to generate higher cumulative sales, possibly due to better brand recognition or established customer base.
 - Newer outlets might still be building their clientele and need targeted support.
   
4.Sales by Outlet Size:

 - Medium-sized outlets generally report higher sales than small or high sized ones.
 - This suggests an operational sweet spot in terms of space, staffing, or product range.
   
5.Sales by Outlet Location Type:

 - Tier 1 and Tier 2 cities perform better than Tier 3, reflecting purchasing power and demand in urban and semi-urban markets.
Products with low turnover.
