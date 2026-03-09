# Customer Personality & Marketing Analysis - Project 2

## Overview
This project focuses on **customer segmentation and personality analysis** using data cleaning techniques in Python and interactive visualization dashboards in Tableau. The analysis reveals customer spending patterns, demographics, and marketing campaign effectiveness to enable data-driven marketing strategies.

## Project Objective
- Clean and prepare raw customer data for analysis
- Identify customer personality traits through behavioral analysis
- Analyze spending patterns across product categories
- Evaluate marketing campaign effectiveness
- Enable data-driven customer segmentation for targeted marketing

## Dataset Information

### Source Data
- **File**: `ifood_df.csv` (raw customer data)
- **Records**: 2,205 customer records (after cleaning)
- **Data Cleaning Date**: March 9, 2026

### Key Features
The cleaned dataset includes the following customer attributes:

**Demographic Information:**
- Age, Marital Status, Education Level
- Income, Customer Days (tenure)

**Spending Data (Mnt = Amount spent):**
- Wines, Fruits, Meat Products, Fish Products
- Sweet Products, Gold Products
- Total Spending (MntTotal, MntRegularProds)

**Purchase Behavior:**
- Number of Web Purchases
- Number of Catalog Purchases
- Number of Store Purchases
- Number of Deals Purchases
- Web Visits per Month
- Recency (days since last purchase)

**Marketing Campaign Response:**
- AcceptedCmp1 through AcceptedCmp5 (5 marketing campaigns)
- Campaign Response Rate
- Total Campaigns Accepted (AcceptedCmpOverall)
- Customer Complaints

**Data Quality:**
- Z_CostContact (standardized contact cost)
- Z_Revenue (standardized revenue)
- Customer ID (C-Id) for tracking

## Data Cleaning Process

### Steps Performed:
1. **Missing Values**: Removed rows with missing/null values
2. **Duplicate Records**: Identified and removed duplicate rows
3. **Customer ID**: Added sequential Customer ID (C-Id) for Tableau integration
4. **Output**: Exported cleaned data to `ready_for_tableau_project2.csv`

### Python Implementation:
The data cleaning was performed using **Pandas** in Jupyter Notebook:
```python
- Load raw CSV data
- Identify and report missing values
- Count and remove duplicates
- Generate unique customer IDs
- Export cleaned dataset
```

## Tableau Visualizations

### Dashboard: OIB-SIP Project 2 - Customer Personality & Marketing Analysis
**View the interactive dashboard**: [Tableau Public Link](https://public.tableau.com/shared/BJMD5RJQM?:display_count=n&:origin=viz_share_link)

### Key Visualizations:

1. **KPI Dashboard**
   - Distinct Customer Count
   - Total Marketing Spend Across Fleet

2. **Education & Spending Analysis**
   - Spending patterns segmented by education level (2nd Cycle, Basic, Graduation, Master, PhD)
   - Total monthly expenses across education segments

3. **Wealth and Spending Analysis**
   - Customer spending vs. income correlation
   - Income distribution analysis
   - High-value customer identification

4. **Product Performance Bubble Chart**
   - Market basket analysis
   - Product category performance
   - Purchase frequency visualization

5. **Campaign Success Analysis**
   - Marketing campaign acceptance rates (Campaigns 1-5)
   - Campaign response metrics
   - Campaign effectiveness comparison

## File Structure

```
Project2_Customer_Segmentation/
├── README.md                              # Project documentation
├── customerseg.ipynb                      # Jupyter Notebook with data cleaning code
├── ifood_df.csv                           # Raw customer data
└── ready_for_tableau_project2.csv         # Cleaned data (Tableau-ready)
```

## Technologies Used

- **Python 3.x**
  - Pandas - Data manipulation and cleaning
  - Jupyter Notebook - Interactive data analysis environment

- **Tableau Public** - Interactive data visualization and dashboarding

## How to Use

### 1. View the Analysis
- Open the [Tableau Public Dashboard](https://public.tableau.com/shared/BJMD5RJQM?:display_count=n&:origin=viz_share_link) to explore interactive visualizations
- Filter by customer segments, education level, or income to uncover insights
- Download visualizations for presentations

### 2. Review Data Cleaning Process
- Open `customerseg.ipynb` in Jupyter Notebook or JupyterLab
- Execute cells sequentially to understand the cleaning pipeline
- Modify filters and preprocessing steps as needed

### 3. Use the Cleaned Dataset
- `ready_for_tableau_project2.csv` is the production-ready dataset
- Ready for import into Tableau, Power BI, or other BI tools
- All rows are deduplicated and complete with no missing values
- Customer IDs are sequential (C-Id column)

## Key Insights & Next Steps

### Analysis Insights:
- Customer segmentation by spending behavior and demographics
- Education level correlation with marketing response
- Income-based spending patterns
- High-value customer identification through purchase frequency

### Recommended Actions:
- Use customer segments for targeted marketing campaigns
- Focus on high-performing product categories
- Personalize campaigns based on education and income segments
- Optimize campaign spend based on acceptance rate analysis

## Project Metadata
- **Author**: Gururaj Naik (Oasis Infobyte SIP Cohort)
- **Project**: OIB-SIP Project 2
- **Timeframe**: Data created and published on March 9, 2026
- **Status**: Completed - Data cleaning and visualization phase

## Notes
- Data cleaning preserved 2,205 customer records
- All visualizations are interactive in Tableau Public
- Dataset is anonymized with customer identifiers (C-Id)
- Spending data is aggregated and standardized for analysis

---

*For questions or further analysis, refer to the Jupyter Notebook or contact the project owner.*
