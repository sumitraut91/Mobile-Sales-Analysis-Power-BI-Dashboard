📊 Mobile Sales Dashboard – Power BI Project
📌 Project Overview

This project presents an interactive Mobile Sales Dashboard built using Microsoft Power BI to analyze mobile sales performance across different cities, brands, and time periods.

The dashboard provides key insights into sales trends, customer behavior, and payment methods, helping businesses make data-driven decisions.

It helps in understanding:

📈 Sales trends
🏙 City-wise performance
📱 Brand & model insights
💳 Payment behavior
⭐ Customer satisfaction
🎯 Objectives

✔ Analyze overall sales performance
✔ Identify top-performing brands & cities
✔ Track monthly & daily trends
✔ Understand customer ratings
✔ Evaluate payment methods

📂 Dataset Information
Column Name	Description
🏙 City	Sales location
📱 Brand	Mobile brand
📦 Mobile Model	Product name
👤 Customer Name	Buyer
🎂 Customer Age	Age group
⭐ Rating	Customer feedback
💳 Payment Method	Mode of payment
💰 Price Per Unit	Price
🔢 Units Sold	Quantity
💵 Total Sales	Revenue
🆔 Transaction ID	Unique ID
📅 Date	Transaction date
📊 Dashboard Highlights
🔹 KPI Cards
💰 Total Sales: 769M
📦 Total Quantity: 19K
🔁 Transactions: 4K
📊 Average Sales: 40K
🔹 Visual Insights

✨ 📍 Sales by City (Map)
✨ 📈 Monthly Quantity Trend
✨ ⭐ Customer Ratings Distribution
✨ 💳 Payment Method Split
✨ 📱 Sales by Mobile Model
✨ 📅 Daily Sales Trend
✨ 📋 Brand Performance Table

🔹 Filters Available

🎯 Month-wise filter
🎯 Brand filter
🎯 Mobile model
🎯 Payment method
🎯 Customer age

🧮 DAX Measures
Total Sales = SUM(SalesData[Total Sales])

Total Quantity = SUM(SalesData[Units Sold])

Total Transactions = COUNT(SalesData[Transaction ID])

Average Sales = AVERAGE(SalesData[Total Sales])
🧾 Calculated Columns
Month Name = FORMAT(SalesData[Date], "MMMM")

Day Name = FORMAT(SalesData[Date], "dddd")
🛠 Tech Stack
📊 Microsoft Power BI
🗄 SQL
📑 Excel / CSV
📷 Dashboard Preview

📌 Add your screenshot here (already you have it 👍)

![Dashboard](dashboard.png)
🔍 Key Insights

📌 Apple & Samsung lead in sales
📌 Peak sales observed in mid-year months
📌 UPI & Debit Card dominate transactions
📌 High-performing cities drive majority revenue
📌 Ratings are mostly ⭐⭐⭐⭐ and ⭐⭐⭐⭐⭐
