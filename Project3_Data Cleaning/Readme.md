📊 NYC Airbnb Data Cleaning Project
Oasis Infobyte Internship - Task 3
📌 Project Overview
This project focuses on the Data Cleaning and Preprocessing of the "New York City Airbnb 2019" dataset. Raw data is rarely perfect; it often contains missing values, incorrect formats, and outliers. My goal was to transform this "noisy" dataset into a clean, structured version ready for analysis and visualization.

Shutterstock

🛠️ Tech Stack
Language: Python

Library: Pandas, NumPy

Tool: Jupyter Notebook

🧹 Cleaning Steps Performed
1. Handling Missing Values
reviews_per_month: Replaced null values with 0 (since no reviews simply means zero activity).

name & host_name: Filled missing entries with "Unknown" to maintain record integrity.

last_review: Converted this column to a proper DateTime format. Any missing dates were labeled as "Not Applicable".

2. Removing Irrelevant Data
Dropped the id column as it serves as a unique identifier but doesn't provide any statistical value for price or location trends.

3. Data Filtering & Logic
Zero-Price Listings: I discovered several rows where the price was listed as $0. Since an Airbnb stay cannot be free, I filtered these out to ensure my average price calculations remain accurate.

4. Consistency & Deduplication
Standardized all text columns to ensure uniformity.

Ran a check for duplicate rows to prevent "double-counting" in the final report.

📈 Final Result
The dataset was reduced from a "messy" state to a high-quality CSV file.

Before: 4 columns with thousands of null values + invalid $0 prices.

After: 0 Null values across all critical columns and 100% valid pricing data.

📂 Files in this Repository
cleaning.ipynb: The Jupyter Notebook containing the step-by-step Python code.

AB_NYC_2019.csv: The original raw dataset.

Project3_Cleaned.csv: The final, processed dataset.

👨‍💻 Author
Gururaj Ashok Naik
Information Technology Engineering Student