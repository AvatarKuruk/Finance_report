# Financial Performance Dashboard

This project presents an end-to-end Power BI solution designed to analyze financial and operational performance across revenue, profit, geography, and product segments.

The dashboard enables business users to monitor key performance indicators, identify trends, and perform detailed analysis through interactive visuals and drill-through capabilities.

Key Features - 

Executive Summary:
Consolidated view of key metrics including total revenue, total profit, and profit margin
Monthly revenue trends across multiple years
Revenue and profit comparison by business segment
Year-over-Year performance analysis
Interactive filters for country, year, and time period

Geographic Analysis:
Country-level revenue distribution using map visualization
Comparative analysis of revenue, profit, profit margin, and YoY growth
Segment contribution across regions
Tabular breakdown for detailed country-level insights

Product Performance:
Product-wise comparison of revenue, units sold, and profitability
Analysis of average selling price and margin across product categories
Monthly trends across multiple product lines
Tree map visualization to highlight product contribution

Product Detail (Drill-Through Analysis):
Implemented drill-through functionality from summary visuals to product-level analysis
Enables users to navigate from aggregated metrics to detailed product performance
Displays monthly trends, segment contribution, and detailed transactional summaries for selected products
Enhances analytical depth and supports user-driven exploration



Tech Stack:
Power BI Desktop and Power BI Service
DAX (Data Analysis Expressions)
Power Query (M Language)
Data Modeling
Implemented a star schema for efficient querying and scalability
Fact table: Sales data

Dimension tables:
Date
Product
Country
Segment
Optimized relationships to improve performance on large datasets

Key Techniques:
Advanced DAX measures for:
Year-over-Year growth
Profit margin calculation
Time-based analysis
Dynamic slicers and filters
Drill-through navigation for detailed analysis
KPI cards with conditional formatting
Performance optimization for large datasets

Business Insights:
Enterprise segment contributes the highest share of revenue
Profit margins remain consistent across regions at approximately 35 percent
Year-over-Year growth indicates strong business expansion
Seasonal patterns are visible in monthly revenue trends
