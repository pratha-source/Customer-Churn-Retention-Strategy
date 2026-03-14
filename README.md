🎬 Telco Customer Churn: Strategic Retention Pipeline
An End-to-End SQL & Python Analysis to Minimize Revenue Leakage.

📌 Project Overview
This project addresses the critical business challenge of Customer Attrition (Churn). By analyzing ~7,000 subscriber records, I developed a data pipeline that identifies high-risk customer segments and quantifies the financial impact of churn.

The goal was to move beyond simple descriptive statistics and provide actionable recommendations to executive stakeholders.

🛠️ The Tech Stack
Data Engineering: Python (Pandas)

Database: SQLite (Relational Storage)

Analytics: Advanced SQL (CASE Statements, Subqueries, Aggregations)

Visualization: Seaborn, Matplotlib

Reporting: Executive Insight Deck (PDF)

🚀 Key Features & Workflow
1. Data Sanitization & ETL
Converted unstructured TotalCharges strings into numeric floats.

Handled missing values to ensure 100% integrity for SQL mathematical functions.

Migrated data into a local SQLite database for structured querying.

2. Deep-Dive SQL Analytics
I utilized advanced SQL to segment the customer base:

Contract Analysis: Quantified the churn rate disparity between Month-to-Month and Long-term contracts.

VIP Risk Detection: Created subqueries to identify "High-Value" customers (above-average monthly spend) on non-binding contracts.

3. Statistical Storytelling
Using Python, I identified the "Price Ceiling"—the specific monthly cost point where the probability of a customer leaving increases by over 40%.

💡 Top Business Insights
The Contract Gap: Month-to-month subscribers churn at a rate of 42.7%, compared to just 2.8% for two-year contract holders.

The Fiber Optic Paradox: While Fiber Optic is a premium service, it shows a significantly higher churn rate than DSL, suggesting potential service quality or pricing friction in the high-speed tier.

The "At-Risk" Revenue: Over $180k in monthly recurring revenue (MRR) is currently tied to high-spending customers on Month-to-Month plans.
