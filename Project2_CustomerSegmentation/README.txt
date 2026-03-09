================================================================================
   CUSTOMER PERSONALITY & MARKETING ANALYSIS - PROJECT 2
================================================================================

OVERVIEW
--------
This project focuses on customer segmentation and personality analysis using 
data cleaning in Python and interactive visualization dashboards in Tableau. 
The analysis reveals customer spending patterns, demographics, and marketing 
campaign effectiveness for data-driven marketing strategies.

PROJECT OBJECTIVE
-----------------
• Clean and prepare raw customer data for analysis
• Identify customer personality traits through behavioral analysis
• Analyze spending patterns across product categories
• Evaluate marketing campaign effectiveness
• Enable data-driven customer segmentation for targeted marketing

DATASET INFORMATION
-------------------
Source Data:
  File: ifood_df.csv (raw customer data)
  Records: 2,205 customer records (after cleaning)
  Data Cleaning Date: March 9, 2026

Key Features Included:

DEMOGRAPHIC INFORMATION:
  • Age, Marital Status, Education Level
  • Income, Customer Days (tenure)

SPENDING DATA (Mnt = Amount spent):
  • Wines, Fruits, Meat Products, Fish Products
  • Sweet Products, Gold Products
  • Total Spending (MntTotal, MntRegularProds)

PURCHASE BEHAVIOR:
  • Number of Web, Catalog, and Store Purchases
  • Number of Deals Purchases
  • Web Visits per Month
  • Recency (days since last purchase)

MARKETING CAMPAIGN RESPONSE:
  • AcceptedCmp1 through AcceptedCmp5 (5 marketing campaigns)
  • Campaign Response Rate
  • Total Campaigns Accepted
  • Customer Complaints

DATA QUALITY FIELDS:
  • Z_CostContact (standardized contact cost)
  • Z_Revenue (standardized revenue)
  • Customer ID (C-Id) for tracking

DATA CLEANING PROCESS
---------------------
Steps Performed:
  1. Missing Values: Removed rows with missing/null values
  2. Duplicate Records: Identified and removed duplicate rows
  3. Customer ID: Added sequential Customer ID (C-Id) for Tableau
  4. Output: Exported cleaned data to ready_for_tableau_project2.csv

Python Implementation:
  • Load raw CSV data
  • Identify and report missing values
  • Count and remove duplicates
  • Generate unique customer IDs
  • Export cleaned dataset

TABLEAU VISUALIZATIONS
----------------------
Dashboard: OIB-SIP Project 2 - Customer Personality & Marketing Analysis

View Interactive Dashboard Here:
https://public.tableau.com/shared/BJMD5RJQM?:display_count=n&:origin=viz_share_link

Key Visualizations:

1. KPI DASHBOARD
   • Distinct Customer Count
   • Total Marketing Spend Across Fleet

2. EDUCATION & SPENDING ANALYSIS
   • Spending patterns by education level 
     (2nd Cycle, Basic, Graduation, Master, PhD)
   • Total monthly expenses by education segment

3. WEALTH AND SPENDING ANALYSIS
   • Customer spending vs. income correlation
   • Income distribution analysis
   • High-value customer identification

4. PRODUCT PERFORMANCE BUBBLE CHART
   • Market basket analysis
   • Product category performance
   • Purchase frequency visualization

5. CAMPAIGN SUCCESS ANALYSIS
   • Marketing campaign acceptance rates (Campaigns 1-5)
   • Campaign response metrics
   • Campaign effectiveness comparison

FILE STRUCTURE
--------------
Project2_Customer_Segmentation/
├── README.md                              
├── README.txt (this file)
├── customerseg.ipynb                      (Jupyter Notebook - Data Cleaning Code)
├── ifood_df.csv                           (Raw Customer Data)
└── ready_for_tableau_project2.csv         (Cleaned Data - Tableau Ready)

TECHNOLOGIES USED
-----------------
Python 3.x:
  • Pandas - Data manipulation and cleaning
  • Jupyter Notebook - Interactive data analysis environment

Tableau Public - Interactive data visualization and dashboarding

HOW TO USE
----------
1. VIEW THE ANALYSIS
   • Open the Tableau Public Dashboard
   • Filter by customer segments, education level, or income
   • Download visualizations for presentations

   Link: https://public.tableau.com/shared/BJMD5RJQM?:display_count=n&:origin=viz_share_link

2. REVIEW DATA CLEANING PROCESS
   • Open customerseg.ipynb in Jupyter Notebook or JupyterLab
   • Execute cells to understand the cleaning pipeline
   • Modify filters and preprocessing as needed

3. USE THE CLEANED DATASET
   • ready_for_tableau_project2.csv is production-ready
   • Import into Tableau, Power BI, or other BI tools
   • 2,205 deduplicated records with no missing values
   • Sequential Customer IDs in C-Id column

KEY INSIGHTS & RECOMMENDATIONS
--------------------------------
ANALYSIS INSIGHTS:
  • Customer segmentation by spending behavior and demographics
  • Education level correlation with marketing response
  • Income-based spending patterns
  • High-value customer identification through purchase frequency

RECOMMENDED ACTIONS:
  • Use customer segments for targeted marketing campaigns
  • Focus on high-performing product categories
  • Personalize campaigns by education and income
  • Optimize campaign spend based on acceptance rates

PROJECT METADATA
----------------
Author: Gururaj Naik (Oasis Infobyte SIP Cohort)
Project: OIB-SIP Project 2
Timeframe: Created and published March 9, 2026
Status: Completed - Data Cleaning and Visualization Phase

NOTES
-----
• Data cleaning preserved 2,205 customer records
• All visualizations are interactive in Tableau Public
• Dataset is anonymized with sequential customer identifiers
• Spending data is aggregated and standardized for analysis

================================================================================
Questions or further analysis? Refer to the Jupyter Notebook or contact the 
project owner.
================================================================================
