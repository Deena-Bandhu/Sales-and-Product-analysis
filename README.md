# Sales-and-Product-analysis



🔍 Part A – Data Manipulation Summary
1️⃣ Data Understanding

Explored core tables:
orders, customers, order_items, order_payments, products

Verified:

Row counts

Column structure

Sample records

Identified primary & foreign key relationships:

order_id, customer_id, product_id

📌 Outcome: Clear understanding of how transactional data flows across the system.

2️⃣ Analysis-Ready Dataset (orders_enriched)

Created a single denormalized table with one row per order item, combining:

Order details

Customer location

Product category

Pricing & payments

Order status

Key Design Decisions:

Excluded incomplete orders (canceled, unavailable) to reflect realized revenue

Created order_purchase_date for time-based analysis

📌 Why this matters:
This table becomes the single source of truth for BI dashboards.

3️⃣ KPI Computation

Calculated:

Total Orders

Total Revenue

Average Order Value (AOV)

Date Range (min–max)

Yearly performance summary

📌 Business relevance:
These KPIs are exactly what leadership teams track in sales reviews.

4️⃣ Time Series Analysis

Created monthly_sales table:

Orders, revenue, and AOV aggregated by year-month

📌 Used for:

Revenue trend analysis

Seasonality detection

Growth monitoring

5️⃣ Product Category Performance

Built category_performance:

Top 10 categories by revenue

Order volume vs item volume

Average pricing insights

📌 Insight enabled:
Identifies high-impact product categories driving the business.

6️⃣ State-Level Performance

Built state_performance:

Revenue

Orders

Unique customers

AOV by state

📌 Business use:
Helps prioritize regional marketing, logistics, and expansion strategies.

7️⃣ Delivery Performance Analysis

Calculated:

Actual delivery time vs estimated delivery time

Aggregated by customer state

📌 Operational insight:
Identifies logistics bottlenecks and SLA risks.

📊 Part B – BI Dashboard Summary
📄 Page 1: Sales Overview

Includes:

KPI cards (Revenue, Orders, AOV, Customers)

Monthly revenue trend line

Top product categories bar chart

State-wise revenue visualization

Interactive filters (Year, Payment Type, Order Status)

📌 Target audience: Business leaders & sales teams

📄 Page 2: Customers & Delivery

Includes:

Delivery performance by state

Customer revenue breakdowns

Insight text box with key observations

📌 Target audience: Operations & supply chain teams

📈 Key Insights (Example)

Revenue peaked during specific festive months, showing seasonality

A small number of product categories contribute a large share of revenue

Certain states show longer delivery times than estimated, indicating logistics gaps

🤖 Usage of LLMs (Transparency)

Used LLMs only for guidance and structuring

No data was uploaded to any LLM

All code logic was written, verified, and understood manually

Able to explain every transformation and aggregation step

🚧 Challenges Faced

Understanding complex joins across multiple transactional tables

Handling payment duplication at order-item level

Choosing consistent revenue logic (payment vs price)

Designing BI dashboards that are both clean and insightful

🌟 Why I Am a Strong Fit for the Team

I approach analytics problems end-to-end, from raw data to insights.

I focus on business relevance, not just technical correctness.

I ensure clean, reusable, and scalable datasets suitable for BI tools.

✅ Final Note (For Interviewers)

This project mirrors real-world analytics work involving:

Data modeling

KPI definition

Trend analysis

Stakeholder-ready dashboards

I can confidently walk through every decision, assumption, and calculation used in this project.

Help you write the GitHub project description headline

Prepare a verbal explanation script (5–7 minutes) for interviews
