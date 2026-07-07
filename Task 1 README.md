# Project 1: Data Cleaning
**DecodeLabs Data Analytics Internship**

## Overview
Cleaned a 1,200-row e-commerce orders dataset (14 columns) to prepare it 
for analysis in later projects.

## Files
- Uncleaned Dataset — original raw data
- Cleaned Dataset — final cleaned data
- Change Log — record of all changes made

## Cleaning Steps
1. **Date standardization** — Converted all dates to YYYY-MM-DD format. 
   Zero formatting errors across all 1,200 records.
2. **Duplicate check** — Checked OrderIDs for duplicates using Excel's 
   Remove Duplicates function. No duplicates found.
3. **Missing value audit** — Scanned all columns for blanks; found missing 
   values only in Coupon Code.
4. **Coupon Code fixes**:
   - Shipped/Delivered/Cancelled orders with blank Coupon Code → set to "None" 
     (250 entries)
   - Pending orders with blank Coupon Code → set to "Pending" (59 entries)

## Tools Used
Microsoft Excel
## Project Deliverables
https://github.com/GraceKwelle/Decodelabs_tasks/blob/9effa9a35e2328592b7ee1aee44af27e7dcb4c34/Grace%20Anosike%20Decodelabs%20Project%201.xlsx
