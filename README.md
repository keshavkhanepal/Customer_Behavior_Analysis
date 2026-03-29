🛍️ Customer Shopping Behavior Analysis


📌 Overview

This project analyzes customer shopping behavior using transactional data (3,900 records) to uncover patterns in purchasing behavior, customer segmentation, and revenue drivers.

The objective is to help businesses make data-driven decisions to improve sales, customer engagement, and retention strategies.

🎯 Business Problem

A retail company wants to understand:

What drives customer purchases?
How discounts, subscriptions, and shipping impact revenue
How to improve customer retention and loyalty

👉 The goal: Optimize marketing & product strategies using data insights

📊 Dataset
📦 Records: 3,900 transactions
📑 Features: 18 columns
🧩 Includes:
Demographics (Age, Gender, Location)
Purchase details (Item, Category, Amount)
Behavior (Discount, Reviews, Subscription, Shipping)

⚠️ Missing Values:

37 missing values in Review Rating handled using median imputation
🛠️ Tech Stack
Category	Tools Used
Data Analysis	Python (Pandas, NumPy)
Data Querying	SQL (PostgreSQL / MySQL / SQL Server)
Visualization	Power BI
Presentation	Gamma (PPT)
Environment	Jupyter Notebook

🔄 Project Workflow

🧹 1. Data Cleaning (Python)
Loaded dataset using pandas
Handled missing values
Standardized column names
Feature engineering:
Age groups
Purchase frequency

📊 2. Exploratory Data Analysis
Statistical summaries
Trend analysis
Customer behavior insights

🗄️ 3. SQL Analysis

Performed business-driven queries such as:

Revenue by gender
Top-rated products
Discount impact
Subscription vs non-subscription
Customer segmentation

📄 SQL file:

📊 4. Dashboard (Power BI)

Developed an interactive dashboard to visualize:

KPIs (Customers, Avg Spend, Ratings)
Revenue by category
Customer segmentation
Subscription insights

📁 File: customer_behavior_dashboard.pbix

📈 Key Insights
💰 Female customers generate slightly higher revenue
🚚 Express shipping users spend more per order
⭐ Top-rated products drive customer satisfaction
🔁 Loyal customers contribute high value
🧾 Subscribers contribute a significant share of revenue

(Insights derived from analysis & report)

💡 Business Recommendations
🎯 Promote subscription-based offerings
🎁 Introduce loyalty programs
💸 Optimize discount strategies
📢 Focus on high-value customer segments
🛍️ Highlight top-rated products
▶️ How to Run
# Clone the repository
git clone https://github.com/your-username/customer-shopping-analysis.git

# Install dependencies
pip install pandas numpy matplotlib seaborn

# Run analysis
python analysis.py
Database Setup
Import dataset into PostgreSQL/MySQL/SQL Server

Run queries from:
customer_behavior_sql_queries.sql

Dashboard
Open .pbix file in Power BI Desktop

📂 Project Structure
customer-shopping-analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
├── sql/
│   └── customer_behavior_sql_queries.sql
├── dashboard/
│   └── customer_behavior_dashboard.pbix
├── reports/
│   ├── analysis_report.pdf
│   └── presentation.pptx
├── notebooks/
│   └── analysis.ipynb
└── README.md
🏆 What This Project Demonstrates

✔ End-to-end Data Analytics workflow
✔ Python for data cleaning & EDA
✔ SQL for business problem solving
✔ Power BI dashboarding
✔ Business insights & storytelling

📎 Project Assets
📄 Report: Customer Shopping Behavior Analysis.pdf
📊 Presentation: Customer-Shopping-Behavior-Analysis.pptx
🗄️ SQL Queries: Included

🚀 Future Improvements
Add predictive modeling (customer churn / CLV)
Deploy dashboard online
Automate data pipeline

If you like this project, feel free to connect on LinkedIn and give a ⭐ to the repo!
