🧠 Customer Segmentation & Persona Strategy

Tools: Python (Pandas, Scikit-learn, Plotly), Power BI, Excel
Date: August 2025

📋 Overview

This project performs customer segmentation using RFM (Recency, Frequency, Monetary) analysis and KMeans clustering, translating behavioral patterns into actionable personas.

The analysis highlights how businesses can leverage data-driven insights to improve marketing performance, retention strategies, and customer lifetime value.

In addition to the Python analysis, the results were visualized through a Power BI dashboard that provides an interactive and executive-friendly view of customer personas, revenue contribution, and behavioral patterns.

🧰 Workflow
1. Data Cleaning & Preparation

Removed missing or invalid transactions (e.g., cancellations).

Computed Total Revenue per Transaction (Quantity × UnitPrice).

Standardized date formats and ensured unique customer IDs.

2. RFM Calculation

Recency: Days since last purchase.

Frequency: Number of unique transactions per customer.

Monetary: Total revenue contributed by the customer.

3. Segmentation

Applied KMeans clustering on normalized RFM features.

Determined 4 key customer groups using the elbow and silhouette methods.

4. Persona Definition & Strategy

Each segment was interpreted into business personas with actionable strategies for marketing and retention.

5. Visualization

Built interactive plots in Python (Plotly).

Developed a Power BI dashboard for business presentation and executive storytelling.

📊 Power BI Dashboard

Title: Customer Segmentation Dashboard

Features:

KPIs: Total Customers, Avg Recency, Avg Frequency, Avg Monetary, % High-Value Customers.

Charts:

Customer Distribution by Persona (Donut Chart)

Revenue Contribution by Persona (Bar Chart)

Customer Behavior Map (Scatter: Frequency vs Monetary)

Summary Table with conditional formatting for Revenue Share %.

Interactive Filters:

Persona Selector

Cluster Slider

Monetary Tier Slicer (Low / Mid / High spend levels)

Theme: Elegant maroon-beige-gray palette matching professional BI standards.

Interactivity: All visuals respond to slicer filters dynamically for deeper insight exploration.

Key Insights from Dashboard:

Loyal Champions dominate both customer base and revenue contribution.

At-Risk Customers present high reactivation potential.

Recent High Spenders show strong future lifetime value if retention strategies are applied.

👥 Key Personas
Persona	Characteristics	Suggested Strategy
Loyal Champions	Frequent, high-value, recent buyers	Maintain loyalty with VIP perks and early access
Recent High Spenders	New and valuable customers	Encourage repeat purchases with personalized offers
At-Risk Customers	Previously active, now dormant	Reactivation campaigns and discount incentives
Occasional Buyers	Moderate frequency, low spend	Increase engagement via tailored recommendations
📈 Insights

Segmented customers into 4 actionable personas using RFM + KMeans.

Power BI dashboard adds interactive visualization and easy storytelling.

Identified At-Risk and Recent High Spenders as the growth opportunity segments.

Strategic adoption can improve engagement by an estimated 12% QoQ.

📂 Files in This Repository
File	Description
customer_segmentation.ipynb	Main analysis notebook (Python)
Customer_Segmentation_Output.xlsx	Final RFM dataset with cluster & persona labels
Persona_RFM_Summary.html	Interactive Plotly summary
Customer_Segmentation_Dashboard.pbix	Power BI interactive dashboard
README.md	Project overview and documentation
🚀 How to Run

Clone the repository

git clone https://github.com/Appu-Anand/Customer-Segmentation-and-Persona-Strategy.git
cd Customer-Segmentation-and-Persona-Strategy


Run Jupyter Notebook

jupyter notebook customer_segmentation.ipynb


Open Power BI Dashboard

Open Customer_Segmentation_Dashboard.pbix in Power BI Desktop.

Ensure dataset path (Customer_Segmentation_Output.xlsx) is correctly linked.

🌟 Deliverables

Python Analytics Notebook: RFM segmentation and KMeans clustering

Excel Dataset: Labeled customer personas

Power BI Dashboard: Executive-friendly segmentation visualization

Business Recommendations: Persona-level engagement strategy
