# Nata Supermarkets: Customer Analytics (Case Study Analysis)
## About the Project
This project was completed as part of a Business Analytics course assignment, focusing on customer analytics for a retail supermarket looking to drive sales growth and optimize marketing efficiency. Leveraging a comprehensive two-year customer dataset from Nata Supermarkets comprising 2,240 retail customers, the analysis aims to unlock actionable insights that bridge the gap between traditional inventory management and data-driven customer engagement strategies.

The core business challenge centered on understanding customer heterogeneity and translating behavioral patterns into targeted promotional strategies. The retail landscape has become increasingly competitive, with industry leaders like Walmart demonstrating the transformative power of customer segmentation and predictive analytics. Our analysis adopts this same data-driven philosophy to help Nata Supermarkets optimize both promotion targeting and product demand forecasting—two critical metrics directly impacting profitability and customer satisfaction.

## Team Members
- [Mridul Jain](https://github.com/MridulJain1101)
- [Humayun Hamza](https://github.com/HamzaAnalytics)
- [Arnold Kelani](https://github.com/Arnold-Kelani)
- [Simin Zhang](https://github.com/zhngsimin-cloud)

## The Dataset
The dataset (Raw_Data) is provided by the professor itself. This data is originally from Ivey Publishing and the product number is W33836. Title of this data is Nata Supermarkets: Customer Analytics - Student Spreadsheet. This spreadsheet supports the product "Nata Supermarkets: Customer Analytics". Prepared by Bissan Ghaddar.

## Analytical Methodology
- Overall Approach:
  Integrated analytics pipeline with three phases — customer segmentation, demand forecasting, and promotion optimization — to maximize business value.
- Customer Segmentation through K-means Clustering:
    - Engineered 17 behavioral and demographic features; removed outliers, retaining 838 customer records.
    - Analyzed spending across 6 product categories and 3 purchase channels.
    - Optimal cluster count: K = 2 (Silhouette Score = 0.2548) for best interpretability.
    - PCA visualization confirmed clear segment separation.
- Demand Forecasting using Exponential Smoothing:
    - Modeled spending and promotion response as time series.
    - Simple Exponential Smoothing: baseline MAPE = 12.8% (total spending).
    - Holt’s Linear Trend Model: improved MAPE to 5.3%, capturing trend patterns.
    - Promotion response forecasting (SES): MAPE = 6.7%, indicating weak trend behavior.
    - Enables proactive inventory and stock planning.
- Promotion Optimization through Mathematical Programming:
    - Designed constrained optimization model to maximize incremental profit under budget limits.
    - Incorporated segment-specific costs and response rates across 4 customer segments and 4 promotion types.
    - Derived optimal allocation of promotional spend, ensuring evidence-based marketing ROI.

## Key Findings
- Two clear customer segments identified:
  - Cluster 0: “Value-Oriented Mainstream” – 196 customers, avg income $43,426, moderate spend, price-conscious, balanced online/offline, moderately promo-sensitive.
  - Cluster 1: “Premium Quality-Seeking” – 642 customers, avg income $32,471, spend 2.1x more on premium wines, prefer in-store, lower promo sensitivity, higher basket value.
- Demand patterns: Wines lead with 2,452 units/year sold; gold products are lowest at 243 units/year.
- Forecasting insight: Including trend components significantly improves demand forecast accuracy, crucial for inventory planning in shifting preference environments.
- Optimized promotions – Premium segment: Highest profit from VIP loyalty programs and premium bundles, yielding $8 incremental profit per targeted customer.
- Optimized promotions – Value segment: Better response to family bundles and online coupons, driving strong volume-based returns despite lower per-customer margin.
- Overall impact: Segment-based strategy lifts expected profit to $48,100 while using only $16,400 of promo budget, achieving a 2.9x return on promotional spend.Demand patterns: Wines lead with 2,452 units/year sold; gold products are lowest at 243 units/year.

## Business Impact & Recommendations
This customer analytics framework enables Nata Supermarkets to transition from generic, company-wide promotional campaigns to precision marketing strategies tailored to distinct customer segments. By aligning product assortment, promotional messaging, and inventory allocation with identified customer preferences, the retailer can simultaneously improve customer satisfaction through more relevant offers and optimize profit through better targeting efficiency. The integration of demand forecasting with customer segmentation ensures inventory decisions reflect not just historical buying patterns but anticipated future demand contingent on segment-specific promotional responses.

Implementing this framework positions Nata Supermarkets to compete more effectively against data-driven competitors by converting the accumulated customer history into strategic competitive advantages in an increasingly crowded retail landscape.
