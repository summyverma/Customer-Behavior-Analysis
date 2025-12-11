# Customer-Behavior-Analysis
Data Analytics Projects Showcasing Customer Behavior Analysis Using Ms Excel,Python,MySQL,PowerBi,Ms Powerpoint
## 📊 Customer Shopping Behavior Analysis – Data Analytics Project
**🔍 Overview**

This project analyzes customer shopping behavior using a dataset of 3,900 transactions across multiple product categories.
The objective is to understand spending patterns, customer segments, product preferences, discount usage, and subscription impact.

The project covers the full data analytics lifecycle:

Loading & exploring the dataset in Python

Cleaning, transforming, and preparing data

Running business-focused SQL queries in MySQL

Creating an interactive Power BI dashboard

Building a written report

Preparing a presentation using Gamma




**📂 Dataset**

The dataset contains 3,900 records and 18 columns.
Key attributes include:

Demographics: age, gender, location, subscription_status

Purchase details: product, category, amount_spent, season, size, color

Behavioral features: discount_used, prior_purchases, buying_frequency, review_rating, shipping_type

Missing values: 37 missing entries in the review_rating column 

Customer shopping behavior anal…

This dataset provides enough depth to explore customer behavior and build data-driven insights.



**🧰 Tools Used**

Python (Pandas, NumPy, Matplotlib/Seaborn) – EDA & cleaning

MySQL – Querying business insights

Power BI – Visualization dashboard

MS Word / PDF – Final report

Gamma – Presentation slides

GitHub – Version control & portfolio showcase
<img width="1408" height="652" alt="Screenshot 2025-12-09 085134" src="https://github.com/user-attachments/assets/dcdf6542-a4bb-4ec0-989c-dd7ff7ca957c" />


🪜 Project Steps

**1. Exploratory Data Analysis (Python)**

Loaded dataset using pandas

Reviewed structure using .info() and .describe()

Identified missing values → filled missing review_rating with median rating per product category

Cleaned column names to snake_case for consistency

Created new derived features:

age_group (binned age ranges)

purchase_frequency_days (difference between transactions)

Removed redundant fields like promo_code_used (overlapping with discount_applied)

Exported cleaned dataset into MySQL database for further analysis 

Customer shopping behavior anal…

**2. SQL Analysis (MySQL)**

Executed multiple business-oriented queries such as:

Revenue by gender

High-spending discount users → Identified 839 customers who used discounts but still spent above average 

Customer shopping behavior anal…

Top-rated products

Spending comparison: Standard vs Express shipping

Subscribers vs Non-subscribers: revenue & avg spend differences

Most discount-dependent products

Customer segmentation: New vs Returning vs Loyal customers

These SQL insights helped validate patterns identified during Python EDA.

**3. Power BI Dashboard**

An interactive dashboard was created to visually explore:

Sales trends and total revenue

Customer groups by gender, age, and subscription

Product category performance

Discount usage and high-value customer patterns

Rating distribution & shipping preferences

The dashboard enables quick decision-making for marketing and business teams.

**4. Report Creation**

A written report summarizes:

Business questions

Analytical approach

Key findings from Python, SQL, and Power BI

Actionable recommendations for improving customer retention, discount strategy, and product positioning

**5. Presentation (Gamma)**

A clean, professional slide deck was designed in Gamma to communicate:

Project purpose

EDA results

SQL insights

Dashboard highlights

Final conclusions

This presentation is suitable for interviews, stakeholders, and portfolio showcase.

**🖥 Results & Insights**

Some key outcomes include:

Discount users can still be high-value customers (839 identified)

Express shipping customers showed higher average spend

Subscribers generated more revenue per customer

Certain products were highly dependent on discounts

Product ratings influenced repeat purchase behavior

(Full insight details available in the report and dashboard.)
