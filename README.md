# 💹 Customer Segmentation & Profitability Dashboard (Retail Banking)

An interactive Tableau dashboard designed for a **retail bank** to monitor **customer profitability**, segment behavior, product holdings, and channel preferences across regions and time. Built with a focus on business storytelling, actionable insights, and KPI monitoring.

---

## 📌 Project Objective

This project simulates a real-world banking analytics scenario where decision-makers can track:

- Profitability by **Customer Segment**
- Revenue contribution by **Product Type** (Loans, Deposits, Credit Cards, Investments)
- Customer **Channel Preferences** (Mobile, Web, Branch)
- **Monthly trends** in Profitability
- Regional comparisons and dynamic filters

---

## 🗂️ Dataset Description

Mock data of **1 million+ banking customers**, generated with Python. It includes realistic distributions, null values, and duplicates to mimic real-world inconsistencies.

| Column Name       | Description                              |
|-------------------|------------------------------------------|
| `Customer_ID`     | Unique ID for each customer              |
| `Segment`         | HNW, Mass Affluent, Students, Seniors    |
| `Region`          | North, South, East, West                 |
| `Channel`         | Mobile, Web, Branch                      |
| `Month`           | Monthly granularity (Jan-24 to Dec-24)   |
| `Deposits`        | Total deposit amount                     |
| `Loans`           | Total loan amount                        |
| `Credit_Cards`    | Number of active credit cards            |
| `Investments`     | Investment amount                        |
| `Profit`          | Derived metric (see below)               |

**Profit Formula:**

```text
Profit = (Deposits * 1%) + (Investments * 2%) - (Loans * 0.5%)

🛠️ Tools Used
Tableau Public – Interactive dashboard creation

Python (Pandas, NumPy) – Data simulation, cleaning, and manipulation

Git & GitHub – Version control and portfolio publishing

📊 Dashboard Features
✅ KPI Tiles:
Total Customers

Total Profit

Average Profit per Customer

✅ Visualizations:
📈 Line Chart: Monthly Profit Trend

📊 Bar Chart: Profit by Customer Segment

🧩 Heatmap: Segment vs Channel Profitability

📦 Product Holding Distribution by Segment

🌍 Region-wise Profitability Trends

✅ Filters:
Month

Region

Segment

Product Type

Channel

🧠 Key Insights Enabled
Which customer segments are most profitable?

Are certain regions underperforming?

Are digital channels outperforming branches in terms of profit?

Which products contribute most to profitability?

How does customer behavior evolve month-over-month?

Author: Nandan Choudhary
