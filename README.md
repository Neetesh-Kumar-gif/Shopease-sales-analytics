# Shopease-sales-analytics
End-to-end SQL + Power BI sales analytics project | PostgreSQL | DAX | 2-page dashboard
# ShopEase Sales Analytics Dashboard

## Project Overview
End-to-end data analytics project simulating a real e-commerce 
business intelligence workflow using PostgreSQL and Power BI.

## Business Problem
ShopEase leadership needed visibility into sales performance, 
customer behaviour, and category profitability to make 
data-driven decisions for Q4 planning.

## Tools Used
- **Database**: PostgreSQL 18
- **BI Tool**: Power BI Desktop
- **Languages**: SQL, DAX

## Dataset
- 200 customers | 35 products | 1,000 orders | 1,624 order items
- 5 product categories: Electronics, Furniture, Kitchen, Clothing, Beauty
- Date range: Jan–Dec 2023

## Key Business Insights
1. Electronics drives 52% of total revenue (₹1.08 Cr) 
   with the highest profit margin at 32.88%
2. June revenue peaked at ₹23.3L — 53% MoM growth, 
   needs investigation for replication
3. 75.5% of customers are HIGH value (>₹50K spend) — 
   retention strategy critical
4. Discount rates are uniform across categories (6–8%), 
   suggesting margin differences are product-driven not pricing-driven
5. Hyderabad is the top revenue city at ₹23L, 
   3x the revenue of bottom cities

## SQL Concepts Used
SELECT, WHERE, GROUP BY, ORDER BY, JOINS, CASE WHEN, 
Subqueries, CTEs, Window Functions (RANK, LAG, PARTITION BY), 
Views, NULLIF, COALESCE, Date Functions

## Power BI Features Used
Live PostgreSQL connection, Star schema modeling, 
DAX measures (CALCULATE, DIVIDE, DISTINCTCOUNT), 
Slicers, Conditional formatting, Top N filters, 
Multi-page dashboard, KPI cards

## Dashboard Pages
**Page 1 — Executive Summary**: Revenue KPIs, monthly trend, 
category performance, profit margins, top cities

**Page 2 — Customer Analysis**: Customer segmentation, 
acquisition trend, city-wise value distribution, payment modes
