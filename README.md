# BlinkIT-Grocery-Data-Analysis
##1. Background and Overview
BlinkIT, a quick-commerce grocery delivery service, operates in a highly competitive market that thrives on efficiency, customer satisfaction, and accurate forecasting. This project analyzes BlinkIT's operational and customer data to identify performance trends, optimize decision-making, and uncover revenue growth opportunities.

This analysis uses raw transaction-level data from the company’s order management system and is supplemented by a Power BI dashboard for interactive visualization and stakeholder engagement.

An interactive PowerBI dashboard can be downloaded here [here](https://github.com/KagisoSegobye/BlinkIT-Grocery-Data-Analysis/blob/main/blinkit.pbix)


## 2. Data Structure Overview
The dataset consists of multiple fields representing transactions, customer behaviors, product attributes, and operational metrics. Key columns include:

Order ID, Customer ID: Unique identifiers for each transaction and customer

Product Name, Category: Granular item-level data

Quantity, Price, Total Value: Purchase metrics

Order Date, Delivery Status, Region: Operational timeline and logistics

Payment Type, Discounts, Profit: Financial and promotional data

The data was cleaned and modeled to create key relationships and hierarchies. Time intelligence and DAX measures were developed in Power BI to enable slicing and trend analyses by region, category, and time.

## 3. Executive Summary
Key high-level findings:

Top-selling categories: Fresh fruits & vegetables and dairy products dominate revenue share.

Customer frequency: A small cohort of loyal customers contributes a significant percentage of monthly revenue.

Order timing: Peak order volume occurs during weekends and late evenings.

Delivery delays: Certain regions consistently show higher late deliveries, impacting customer satisfaction.

Discount impact: Products with promotions see ~35% higher sales volume but reduced profit margins by ~18%.

BlinkIT Overview.png


!https://github.com/KagisoSegobye/BlinkIT-Grocery-Data-Analysis/commit/8aaa7f9243852d03ac8137860a6c238a8f2c6199

## 4. Insights Deep Dive
🛒 Product Performance
Top 10 SKUs contribute over 40% of total revenue.

Low-performing items occupy inventory without moving for more than 30 days on average.

Bundled items tend to outperform individual purchases in repeat orders.

🌍 Regional Analysis
North and West zones contribute ~65% of total revenue but also report the highest delivery failure rates.

South zone shows better operational efficiency and higher repeat purchases per customer.

📈 Profitability Insights
Items with a discount >15% show a drop in margin beyond sustainable thresholds.

Cash on Delivery (COD) orders have a slightly higher cancellation rate (~8%) than prepaid ones.

📅 Time-based Trends
Monthly growth plateaued after Q2, with slight seasonal upticks.

Delivery window optimization opportunities were identified based on time-of-day trends.

## 5. Recommendations
Based on the analysis:

Optimize SKU Portfolio: Eliminate or bundle slow-moving items and promote high-margin items.

Revise Discount Strategy: Cap high-discount offers to ≤15% for non-essential products to retain margins.

Improve Logistics in Key Regions: Invest in local partnerships or route optimization in underperforming regions.

Incentivize Prepaid Orders: Promote prepaid models with loyalty points to reduce cancellations.

Enhance Weekend Ops: Increase delivery staff during peak order windows (Friday to Sunday evenings).

Customer Retention Program: Develop a tiered loyalty program based on order frequency and spend.

📌 Caveats and Assumptions
Incomplete Customer Demographics: The dataset lacks detailed demographic data, limiting behavioral segmentation.

Seasonality Limitations: Historical data may not cover full seasonal cycles for robust trend analysis.

Delivery Delay Attribution: Assumes delays are primarily logistic; does not account for external factors (e.g., weather).

Profit Calculations: Profit margins are estimated using available pricing and discount data and may exclude overhead costs.
