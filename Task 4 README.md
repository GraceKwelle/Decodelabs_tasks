# Project 4: E-Commerce Performance Dashboard
**DecodeLabs Data Analytics Internship**

## Overview
This project focuses on analyzing 1,200 raw e-commerce orders to uncover key pricing trends, traffic sources, customer behavior patterns, and high-value transactional outliers. The cleaned insights were aggregated into an interactive, executive-grade spreadsheet dashboard designed to drive operational and marketing decisions.

## Key Findings
* **Revenue Distribution:** Right-skewed `TotalPrice` distribution, indicating a high concentration of standard orders balanced by high-value transactions (Mean: **$1,053.97** vs. Median: **$823.62**).
* **Outlier Tracking:** Identified **8 statistical outliers** exceeding **$3,330.41**, heavily driven by major transactions such as order `ORD200789` (**$3,456.40**).
* **Product Performance:** * 👑 **Chairs** drive the highest sales revenue (**$48,660.98** across 251 cart items).
  * 📉 **Phones** represent the lowest revenue category (**$28,023.26** across 165 cart items).
* **Acquisition & Payments:** **Instagram** serves as the primary driver of referral acquisition traffic, while **Online Banking / Credit Cards** lead as the most utilized payment options.

## Method & Workflow
1. **Data Cleaning & Preparation:** Standardized dates into a clean `YYYY-MM-DD` layout, handled missing/null tracking parameters, eliminated duplicates, and enforced numerical values for transactional precision.
2. **Descriptive Statistics:** Computed central tendency metrics (Mean, Median) and implemented an **IQR-based (Interquartile Range) outlier detection funnel** in Excel.
3. **Pivot Calculations:** Aggregated raw transactional records into summarized categorical data to extract total items sold and overall total revenue per product bucket.
4. **Interactive Visualization:** Designed a professional, clean canvas dashboard using an executive color palette (Charcoal & Steel Blue) with gridlines disabled, structured with explicit KPI Summary Cards, Pivot Charts, and interactive Slicers.

## Tools Used
* **Microsoft Excel:** Pivot Tables, descriptive

## Project Deliverables 
https://github.com/GraceKwelle/Decodelabs_tasks/blob/6fb1dbbf17813e6734e4788e9343fffcd56ed275/Grace%20Anosike%20Decodelabs%20Project%204.xlsx
