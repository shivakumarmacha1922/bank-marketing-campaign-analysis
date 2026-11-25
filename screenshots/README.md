# Bank Marketing Campaign Analysis | Power BI

## Project Overview
This project analyzes a bank's direct marketing campaigns to understand customer behavior and term deposit subscription performance. An interactive Power BI report was developed to explore campaign outcomes, customer demographics, contact channels, and previous campaign interactions.

## Business Problem
The bank wants to understand which customer segments and campaign characteristics are associated with higher term deposit subscription rates. The analysis aims to identify patterns that can support better customer targeting and marketing decisions.

## Dataset
- Dataset: Bank Marketing Campaign Dataset
- Original records: 41,188
- Records after removing exact duplicate rows: 39,404
- Target variable: `y` (Yes/No subscription outcome)

## Tools & Technologies
- Power BI
- Power Query
- DAX
- Data Cleaning
- Data Visualization

## Data Preparation
- Removed 1,784 exact duplicate rows.
- Checked data types, blank values, and data quality.
- Retained unknown values as categories.
- Reviewed campaign and previous-contact fields.
- Created an Age Group calculated column.
- Created DAX measures for key performance indicators.

## Dashboard Pages

### 1. Campaign Overview
- Total campaign records
- Total subscriptions
- Subscription rate
- Average campaign contacts
- Previously contacted records
- Monthly subscription trends

### 2. Customer Analysis
- Subscription rates by job
- Education and marital status
- Age group analysis
- Housing loan and personal loan comparisons
- Interactive customer filters

### 3. Campaign Performance
- Subscription rate by contact channel
- Campaign contact frequency
- Previous campaign outcomes
- Previous contact analysis
- Interactive campaign filters

## Key Performance Indicators

| Metric | Result |
|---|---:|
| Total Records | 39,404 |
| Total Subscriptions | 4,598 |
| Subscription Rate | 11.67% |
| Non-Subscriptions | 34,806 |
| Average Campaign Contacts | 2.62 |
| Previously Contacted Records | 5,546 |

## Key Learning Outcomes
- Practical experience with Power Query data cleaning.
- Created and used DAX measures for business KPIs.
- Designed interactive multi-page Power BI dashboards.
- Analyzed customer segments and campaign performance.
- Translated data into business-oriented insights.

## Project Files
- Power BI report (`.pbix`)
- Dashboard screenshots

## Conclusion
This project demonstrates an end-to-end data analysis workflow using Power BI, from data preparation and KPI development to interactive dashboard design and business insights.
