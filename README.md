# Day 8

🎯 Day 8 – One Project a Day Until I Get Hired

🧮 Customer Revenue & Lifetime in SQL (Superstore Dataset)

Today I built a simple but powerful SQL query to extract customer-level insights from mock Superstore data using SQLite.


✅ What I accomplished:

 - Summed total revenue per customer

 - Calculated each customer’s first and last purchase date

 - Derived their active lifespan (in days) using SQLite's JULIANDAY() function

 - Sorted all customers by spending to find the most valuable ones

🔍 Interesting challenge:
The OrderDate column came in the format DD/MM/YYYY, but SQLite only recognizes YYYY-MM-DD. I had to transform it using SUBSTR() to make proper date comparisons and aggregations work. A nice reminder that cleaning dates can be as tricky as cleaning numbers!

📊 These foundational metrics are key for calculating Customer Lifetime Value (CLV), identifying retention patterns, and segmenting high-value users — even in mock data.

🕒 As always, I limited myself to ~1 hour of focused work to simulate fast-paced, real-world challenges.

📂 Files & SQL Query: 🔗 https://github.com/elem86/day8
📁 Dataset: Superstore Sales (Kaggle)

![image](https://github.com/user-attachments/assets/9a6680e3-288e-43cc-89ee-867ab78c25c3)


#SQL #SQLite #DataAnalytics #CustomerInsights #CLV #OneProjectADay #OpenToWork #Day8 #DataAnalysis #SuperstoreData
