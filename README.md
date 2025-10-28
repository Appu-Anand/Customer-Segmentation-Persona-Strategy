# 🧠 Customer Segmentation & Persona Strategy

**Tools:** Python (Pandas, Scikit-learn, KMeans, Plotly), Excel  
**Date:** August 2025  

## 📋 Overview
This project performs customer segmentation using RFM (Recency, Frequency, Monetary) analysis and KMeans clustering to identify distinct customer personas and guide marketing strategy.

The analysis demonstrates how behavioral data can drive targeted marketing, retention campaigns, and personalized engagement strategies.

---

## 🧰 Workflow
1. **Data Cleaning & Preparation** – Removed missing values, cancellations, and computed total revenue per transaction.  
2. **RFM Calculation** – Computed Recency (days since last purchase), Frequency (transactions), and Monetary (total spend) per customer.  
3. **Segmentation** – Applied KMeans clustering to group customers into four meaningful segments.  
4. **Visualization** – Built interactive dashboards using Plotly for insight exploration.  
5. **Persona Definition & Strategy** – Interpreted each segment into a human-readable persona with business recommendations.

---

## 👥 Key Personas
| Persona | Characteristics | Suggested Strategy |
|----------|-----------------|--------------------|
| **Loyal Champions** | Frequent, high-value, recent buyers | Maintain loyalty with VIP benefits and early access |
| **Recent High Spenders** | New and valuable customers | Encourage repeat purchases via personalized offers |
| **At-Risk Customers** | Previously active, now dormant | Win back with reactivation campaigns |
| **Occasional Buyers** | Moderate frequency, low spend | Boost with targeted recommendations |

---

## 📈 Insights
- Segmented customers into 4 actionable personas using RFM + KMeans  
- Identified *At-Risk* and *Recent High Spenders* as the two segments with the greatest growth potential  
- Proposed strategies that could improve engagement by **~12% quarter-over-quarter**

---

## 📂 Files in This Repository
| File | Description |
|------|--------------|
| `customer_segmentation.ipynb` | Main analysis notebook |
| `Customer_Segmentation_Output.xlsx` | Final dataset with cluster & persona labels |
| `Persona_RFM_Summary.html` | Interactive Plotly dashboard |
| `README.md` | Project overview and documentation |

---

## 🚀 How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/yourusername/customer-segmentation-rfm.git
