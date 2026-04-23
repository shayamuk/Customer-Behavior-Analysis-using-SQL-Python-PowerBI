# 📖 Project Overview

This project delivers an end to end data solution analyzing the purchasing patterns of 3,900 customers. The goal is to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior to guide strategic business decisions. Using a hybrid approach, I developed a Python-based ETL pipeline to process and cleaned raw data, a MySQL database for deep-dive analytical querying, and a Power BI dashboard for executive reporting.

# 🎯 Business Objective

The project was designed to solve three critical retail challenges:

1. Automated Data Integration: Streamlining the flow of raw transactional data into a structured database.

2. Customer Segmentation: Identifying high-value demographics and loyalty tiers (New, Returning, Loyal).

3. Revenue Optimization: pin-pointing the most profitable product categories and demographic intersections.


# 📊 Dataset Description

The analysis utilizes a retail dataset containing:

1. Transactional Records: Purchase amounts, items, categories, and payment methods.

2. Customer Attributes: Age, gender, location, and subscription status.

3. Service Metrics: Shipping types, discount applications, and review ratings.

4. Missing data - 37 values in Review Rating column


# 🛠 Tools & Skills Used

1. Data Preparation,Modeling & Exploratory Data Analysis (Python): Clean and transform the raw dataset for analysis.

2. Data Analysis (SQL): Simulate business transactions, and run queries to extract insights on customer segments, loyalty, and purchase drivers.

3. Visualization & Insights (Power BI): Build an interactive dashboard that highlights key patterns and trends, enabling stakeholders to make data-driven decisions.

# ⚙️ What I built

In Python (Jupyter Notebook):

Filled missing review ratings using category-wise median
Created an age_group column (Young Adult → Senior) using quartile binning
Mapped purchase frequency text to number of days
Removed a duplicate column after verifying it was redundant
Loaded the clean data into a MySQL database

In SQL (10 business queries):

Revenue split by gender and age group

Top 5 products by average review rating

Customers who used discounts but still spent above average

Subscription vs. non-subscription spend comparison

Customer segmentation — New, Returning, and Loyal buyers

Top 3 products per category by order volume

Products with the highest discount usage rates

# 📈 Key Insights & Business Impact

💰 Revenue Analysis

* Male customers drive 67.7% of total revenue ($157,890 vs $75,191 from females), pointing to a core demographic to protect and a growth opportunity in female engagement

* Clothing is the top-revenue category at $104,264 (44.7% of total), followed by Accessories at $74,200

*Adults (18–31) contribute the highest revenue at ~$62K, making them the most commercially valuable segment

🎯 Customer Segmentation

* 80% of the customer base (3,116 out of 3,900) are Loyal buyers (10+ previous purchases) — this is a strong retention foundation but signals limited new customer acquisition

* Young Adults contribute the highest revenue at $62,143 — roughly $6,000 more than the next closest group (Middle-Aged at $59,197), making them the primary target demographic

* Only 83 customers (2.1%) are first-time buyers — the business is heavily dependent on repeat customers with almost no new customer pipeline

🔁 Loyalty & Subscription

* 73% of customers (2,847) have no subscription — they collectively account for $170,436 in revenue, meaning there is a large high-value pool that hasn't been converted

* Subscribed customers number just 1,053 yet still generate $62,645 — converting even 10% of non-subscribers could add ~$17,000 in recurring revenue

🏷️ Discount Strategy

* 50% of discount users still spent above the average purchase amount ($59.76) — discounts are not purely attracting low-spend customers, making them a viable upsell tool

* Hats, Sneakers, and Coats have the highest discount rates (~49–50%) — nearly 1 in 2 purchases of these items use a discount, which may indicate pricing pressure or over-promotion in these SKUs

* Non-discounted purchases average $60.13 vs $59.28 for discounted ones — a small $0.85 gap, suggesting discounts aren't significantly cannibalizing order value

🚚 Logistics & Shipping

* Express shipping customers spend $2 more on average ($60.48) than Standard shipping customers ($58.46) — a small but consistent signal that faster-shipping customers are slightly higher-value buyers
 
⭐ Product Quality

* Gloves (3.86), Sandals (3.84), and Boots (3.82) are the top-rated products — consistently above the overall average of 3.75, making them trust-anchor items ideal for featuring in campaigns

📌 If this project helped you, consider giving it a star! ⭐

