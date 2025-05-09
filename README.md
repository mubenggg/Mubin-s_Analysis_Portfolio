## mubin-s_portfolio

Welcome! I'm glad you're here.  
This section showcases a collection of my data analysis projects — from SQL queries and Power BI dashboards to Excel automation tools.  
Each project reflects real-world business problems I've worked on, especially in the area of debt recovery analytics.  
Feel free to explore, learn, and reach out if something catches your eye!

# Project 1 : Product Manager Performance Dashboard

## 🧠 Project Background

Pasadana, a financial recovery and debt collection agency, oversees a large portfolio of non-performing loan (NPL) accounts from various financial institutions. Under the supervision of Product Manager Nizam, this project aims to evaluate the collection performance and recovery potential of a group of 12,640 accounts totaling RM241.31 million in outstanding debt.

The company manages multiple product types—such as RHB CCFP NORMAL, RHB HP, RHB ASB, and RHB Mortgage (HL)—each contributing differently to overall performance. The dashboard is designed to provide visibility into key collection indicators such as current collection, paying accounts, forecasted recoveries (PTP), and closure performance, all while tracking CRO-level and product-level contribution trends.

This project synthesizes real-time collection data and historical performance to improve decision-making, resource allocation, and strategy formulation in pursuit of higher recovery rates and operational efficiency.

Key Insights and Evaluation Areas:
- Collection Performance Analysis: Assessment of current collection figures, paying account trends, and comparisons against previous periods to identify performance drops or improvements.
- Product-Level Contributions: Evaluation of collection efficiency across different loan product groups and their impact on the total recovery rate.
- Collector Performance Benchmarking: Analysis of individual CRO performance to identify top performers and areas for coaching or intervention.
- Forecast vs. Reality (PTP Monitoring): Tracking of payment promises and collection forecasts against actual results to gauge prediction accuracy.
- Portfolio Closure Insights: Examination of the number of closed accounts and their relation to collection efforts over time.

The SQL queries utilized to clean, organize, and prepare data for the dashboard can be found [**here**](https://github.com/mubenggg/PM-Dashboard/blob/main/PM%20DASHBOARD%20(Completed).sql).

## 💼 Executive Summary

![image](https://github.com/user-attachments/assets/66e7c1e3-cfb0-42ea-8646-2942a7dfdc53)

### Overview of Findings

As of the latest reporting date, the collection performance under Product Manager Nizam has shown a significant downturn compared to the previous month. Key performance indicators reflect notable declines in several core areas: Current Collection is down by 44.66%, Paying Accounts have decreased by 34.47%, and Collection Forecast (PTP) has dropped by 31.26%. Additionally, the Closing Value has dropped by over 47.20% compared to two months prior, indicating a considerable slowdown in account resolutions.

Despite the downturn, performance insights at the product and collector level reveal opportunities for recovery. The RHB Mortgage (HL) product demonstrated the highest improvement in performance relative to last month, and Collector B.HAIKALL emerged as the most improved collector with a 106.51% increase in collections. These standout performances suggest that focused strategies and individual contributions can help offset broader performance challenges.

The following analysis explores the contributing factors behind these trends, highlights the most and least performing segments, and identifies actionable recommendations for improving recovery outcomes.

Key Performance Indicators (as of report date):
- Total Accounts Monitored (NOA): 12,640
- Total Outstanding Value (TOS): RM241.31M
- Current Collection: RM72.38K ▼ 44.66%
- Paying Accounts: 211 ▼ 34.47%
- Collection Forecast (PTP): RM231.56K
- Closing (Last Month): RM396.07K ▼ 41.54%
- Closing (Last 2 Months): RM438.53K ▼ 47.20%




# Project 2 : Company Collection Overview

## 🧠 Project Background

As the sole data analyst at Pasadana SDN BHD, a company focused on debt recovery and customer service, I was tasked with designing a centralized and interactive dashboard to monitor and evaluate collection performance over multiple years. Our operations span across various sectors such as Banking, Education, Telco, Corporate, and Consumer.

The primary goal was to give upper management and operations teams a clear, real-time snapshot of total collections, sector-wise contributions, product performance, and collection trends to aid strategic decisions and improve client servicing.

### Key Features

- Interactive filtering by Year and Sector for granular analysis.
- Real-time visibility of performance from both client and product perspectives.
- Easy identification of collection peaks and dips throughout the months.
- Supports strategic planning, performance benchmarking, and operational improvements.

The SQL queries utilized to clean, organize, and prepare data for the dashboard can be found [**here**](https://github.com/mubenggg/Company-YTD-Collection/blob/main/Report%20YTD%20Collection.sql).


## 💼 Executive Summary

![image](https://github.com/user-attachments/assets/9c3f1183-1c01-498d-bf49-6eee57a912dc)

### Overview of Findings
Between January 2023 and March 2025, the company’s monthly collections demonstrated varied performance across key sectors, including Banking, Education, Telco, and Others. Following a period of steady decline in mid-2023, there was a notable surge in collection performance in Q2 and Q3 of 2024, peaking in August 2024 with RM9.3M in total collections — the highest in the period analyzed.

Key statistical analysis revealed a high variance in monthly collection values, indicating inconsistent collection patterns across months. While the Banking sector consistently contributed the highest amount, sharp increases from the Education sector in 2024 significantly boosted overall performance.

However, since October 2024, collections have shown a declining trend, with March 2025 closing at RM5.2M, a 44% drop from the August 2024 peak. This downward trend indicates a need for renewed focus on recovery efforts and sector-specific strategy alignment.

The following insights have been derived from the interactive Power BI dashboard:

- Highest monthly collection: RM9.3M (August 2024)
- Lowest monthly collection: RM4.4M (April 2023)
- Total Collection (2023 – March 2025): Approx. RM159M+
- Major contributors: Banking, followed by Education in recent months
- Statistical Spread (Variance): High — suggesting potential opportunities for process standardization or targeting key high-performing months/sectors

This dashboard provides a foundational tool for operational planning, performance review, and executive decision-making, helping teams to identify both peak performance periods and underperforming segments.


# Project 3 : NPL Product Monitoring

## 🧠 Project Background

This project focuses on the development of an Excel-based monitoring system for AEON's Non-Performing Loan (NPL) accounts, integrated with Power BI visualizations to provide actionable insights for internal recovery teams.

As part of a debt recovery initiative, AEON outsourced a portfolio of NPL accounts, which were grouped into batches and categorized by delinquency months (D3 to D6). The objective was to recover a targeted percentage of the principal amount, with particular attention to daily collections, payment behavior, and collector performance.

To support this effort, the project involves:

*Organizing NPL accounts into 4 principal-based risk groups (Low, Medium, High).
*Tracking key performance indicators (KPIs) such as:
  -Total number of accounts (NOA)
  -Amount collected
  -Paid vs unpaid accounts
  -Pushback and short-paid accounts
  -Conversion rates (CTC & Payment)
*Monitoring progress against recovery targets set for each group.
*Identifying accounts that fall short of expectations and require follow-up actions.

The end product includes a dynamic dashboard built in Power BI and structured reports for management to track recovery rates and optimize team strategies.

The SQL queries utilized to clean, organize, and prepare data for the dashboard can be found [**here**](https://github.com/mubenggg/AEON-NPL-Monitoring/blob/main/AEON%20NPL.sql)

## 💼 Executive Summary

![AEON NPL](https://github.com/user-attachments/assets/5ed2c754-ebda-4d60-86fa-bc9e573f1969)


### Overview of Findings

The analysis of AEON's NPL accounts across multiple delinquency stages (D3 to D6) revealed a clear trend: the older the delinquency stage, the lower the recovery performance.

Early-stage accounts (D3) showed the highest payment conversion and recovery rates, contributing the most towards the principal recovery target. As accounts aged into D4, D5, and D6, payment activity declined significantly, despite consistently high contact-to-conversion (CTC) rates. This indicates that while collectors were able to reach debtors, converting engagement into actual payments became increasingly difficult.

Additionally, a noticeable portion of accounts fell into the “Low principal” group (< RM3,000), which were more likely to generate smaller payments or short-paid outcomes. Pushbacks and short-paid cases increased in later stages, highlighting challenges in debtor cooperation or financial capacity.

In summary, the findings highlight the critical importance of early intervention. Timely and targeted follow-ups, especially in D3 and D4, can greatly improve collection effectiveness and reduce resource strain on harder-to-recover D5 and D6 accounts.


