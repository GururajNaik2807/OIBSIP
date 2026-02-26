🛍️ Retail Sales Exploratory Data Analysis (EDA)
Oasis Infobyte Internship - Level 1, Task 1
Intern: Gururaj Naik

Role: Data Analytics Intern

🌟 The Mission
The goal of this project wasn't just to crunch numbers, but to uncover the "story" behind 1,000 retail transactions. By performing Exploratory Data Analysis (EDA), I set out to identify who the customers are, what they are buying, and when the business is most profitable. This project serves as a roadmap for data-driven decision-making in a retail environment.

📊 The "Deep Dive" (Actual Data Insights)
Using Python's powerful libraries (Pandas, Matplotlib, Seaborn), I processed the dataset and found some fascinating trends:


The Revenue Engine: The total revenue generated across 1,000 records was $456,000.

The "Whale" Effect: While the middle-of-the-road customer spends about $135 (Median), the average spend is pulled up to $456 (Mean). This tells me that our high-spending "VIP" customers (buying up to $2,000 in one go) are a massive part of our success.

Electronics is King: Out of the three categories (Beauty, Clothing, Electronics), Electronics led the pack with over $156,905 in total sales.

May Madness: Sales peaked in May 2023, reaching a high of $53,150. Understanding what happened in May (promotions? holidays?) is key to repeating that success next year.

The Balanced Shopper: Our audience is almost perfectly split—51% Female and 49% Male—with an average age of 41. This suggests a mature, established customer base.

🛠️ Tools Used
Python (The backbone)

Pandas & NumPy (For data cleaning and math)

Seaborn & Matplotlib (For turning numbers into stories/visuals)

📈 Visualizing the Story
My script generates several key charts to help visualize these insights:

Monthly Revenue Trend: A line graph tracking the pulse of the business month-by-month.

Category Performance: A bar chart that clearly shows Electronics as the top performer.

Customer Demographics: A look at the age distribution to see exactly who we are marketing to.

Correlation Heatmap: A visual check to see how Age, Quantity, and Price interact.

💡 Recommendations for the Business
Based on my analysis, I propose the following:

Target the "Whales": Since high-value transactions are driving the average up, we should launch a premium loyalty program for big spenders.

Inventory Prep: Since May is our strongest month, we should ensure maximum inventory levels and marketing budget are ready by April.

Tech Focus: With Electronics leading sales, we should explore cross-selling beauty or clothing products to our tech-buying audience.

🚀 How to Run
Ensure you have Python installed.

Install requirements: pip install pandas matplotlib seaborn.

Run the script: python eda1.py.