# Sales-Performance-Commission-Dashboard
This repository contains a Sales Reporting and Commission Model built in Microsoft Excel. The project was designed to streamline the tracking of sales transactions, calculate tiered commissions automatically, and provide a visual summary of staff performance.
How it Works
​The model processes a retail dataset through three primary layers:
​The Automation Layer (Formulas)
​Tiered Commission Logic: Used the formula =IF(G11>30, K11*0.2, G11*0.1) to apply different commission rates based on unit price.
​Profit Tracking: Calculated individual profit per line item based on the variance between unit price and sales price multiplied by quantity.
​The Analytical Layer (Pivot Tables)
​Staff Performance: Aggregated total sales price per representative to identify high-volume sellers.
​Categorical Analysis: Segmented data by Product Line and Payment Method (Cash, E-wallet, Credit Card) to understand customer preferences.
​The Visualization Layer (Charts)
​Total Sales Contribution: A 3D Pie Chart provides a proportional view of revenue by sales agent.
​Regional Breakdown: Tracking sales by Branch to monitor urban market penetration.
​Technical Implementation
​Dynamic Formula Logic: Created robust formulas that adjust commission payouts based on changing price thresholds.
​Data Cleaning: Standardized name fields and location tags for uniform reporting.
​Financial Summarization: Used Grand Total calculations to audit the accuracy of individual agent payouts against total branch revenue.
​Impact
​This tool acts as a Business Intelligence (BI) Lite solution, allowing managers to instantly see who their top sellers are and how much commission is owed without manual tallying, significantly reducing the margin for error in payroll and performance reviews.
