SQL Project – Consumer Goods Ad-hoc Insights

🚀 A SQL case study project based on AtliQ Hardwares, a leading computer hardware company.
This project simulates a real-world SQL challenge designed to provide business insights for management decision-making.

It covers:

Writing optimized SQL queries for ad-hoc business requests

Generating reports for sales, finance, and customer insights

Practicing data analysis using realistic datasets

Strengthening both technical (SQL) and analytical problem-solving skills

This project is inspired by an industry-style analytics challenge, focusing on turning raw data into actionable insights.

📌 Business Requests & SQL Solutions
1️⃣ List of markets where customer "Atliq Exclusive" operates in the APAC region
<img src="https://github.com/user-attachments/assets/fba2ad23-84cc-4b8c-ac65-fb59df680293" width="800"/>
2️⃣ Percentage of unique product increase in 2021 vs. 2020
<img src="https://github.com/user-attachments/assets/3ac1258c-9bfb-4325-9c79-5f975bfb3f47" width="600"/>
3️⃣ Unique product counts for each segment (sorted in descending order)

Output fields:

segment

product_count

<img src="https://github.com/user-attachments/assets/4897e7ba-489a-4352-af52-c5393846d84d" width="800"/>
4️⃣ Segment with the most increase in unique products (2021 vs. 2020)

Output fields:

segment

product_count_2020

product_count_2021

difference

<img src="https://github.com/user-attachments/assets/828ef2de-b303-4d15-a59e-0befe6e784d6" width="600"/>
5️⃣ Products with the highest and lowest manufacturing costs

Output fields:

product_code

product

manufacturing_cost

<img src="https://github.com/user-attachments/assets/3eac92b8-c78c-44be-8c79-ed08adec547d" width="700"/>
6️⃣ Top 5 customers with highest average pre-invoice discount % (FY 2021, Indian Market)

Output fields:

customer_code

customer

average_discount_percentage

<img src="https://github.com/user-attachments/assets/910464b6-1c03-4acb-b953-575756d97f06" width="600"/>
7️⃣ Gross Sales Amount report for "Atliq Exclusive" (Monthly trend)

Output fields:

Month

Year

Gross Sales Amount

<img src="https://github.com/user-attachments/assets/de90591a-3c1a-4e63-80d9-9bf2839edcbb" width="800"/>
8️⃣ Quarter of 2020 with maximum total_sold_quantity

Output fields:

Quarter

total_sold_quantity

<img src="https://github.com/user-attachments/assets/7068e634-7fd3-441e-abaf-2df47eb41eb2" width="700"/>
9️⃣ Channel contributing the most to gross sales (FY 2021)

Output fields:

channel

gross_sales_mln

percentage

<img src="https://github.com/user-attachments/assets/3cf806b5-979a-4db9-987a-2bde8edf92eb" width="700"/>
🔟 Top 3 products in each division (by total_sold_quantity in FY 2021)

Output fields:

division

product_code

product

total_sold_quantity

rank_order

<img src="https://github.com/user-attachments/assets/2b5d647a-b4d1-4b4d-8714-f06e828be682" width="800"/>
📊 Key Learnings

Writing efficient SQL queries for business problems

Performing comparative year-over-year analysis

Using SQL window functions for ranking and aggregation

Deriving insights to support data-driven decisions

🛠️ Tech Stack

SQL (MySQL)

Dataset: Consumer Goods (Provided by CodeBasics
)

Visualization: Screenshots from SQL query results

✨ If you found this project useful, don’t forget to ⭐ the repo!
