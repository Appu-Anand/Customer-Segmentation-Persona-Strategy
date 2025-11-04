# 🧠 Customer Segmentation & Persona Strategy  
**Tools:** Python (Pandas, Scikit-learn, Plotly), Power BI, Excel  
**Date:** August 2025  

---

## 📋 Overview  
This project performs customer segmentation using **RFM (Recency, Frequency, Monetary)** analysis and **KMeans clustering**, translating behavioral data into actionable customer personas.

It demonstrates how businesses can use **data-driven insights** to improve marketing performance, retention, and customer lifetime value.  

A fully interactive **Power BI dashboard** was also built to visualize customer segments, revenue contribution, and behavioral patterns for better storytelling and decision-making.

---

## 🧰 Workflow  

### 1. Data Cleaning & Preparation  
- Removed missing or invalid transactions (e.g., cancellations).  
- Computed **Total Revenue per Transaction** (`Quantity × UnitPrice`).  
- Standardized date formats and ensured unique customer IDs.  

### 2. RFM Calculation  
- **Recency:** Days since last purchase.  
- **Frequency:** Number of unique transactions per customer.  
- **Monetary:** Total revenue contributed by the customer.  

### 3. Segmentation  
- Applied **KMeans clustering** on normalized RFM features.  
- Determined **4 key customer groups** using the elbow and silhouette methods.  

### 4. Persona Definition & Strategy  
Converted clusters into **human-readable personas** with actionable business strategies for marketing and retention.  

### 5. Visualization  
- Built **interactive Python dashboards** using Plotly.  
- Designed a **Power BI report** for executive storytelling and business presentation.

---

## 📊 Power BI Dashboard  

**Title:** `Customer Segmentation Dashboard`  

**Features:**  
- **KPIs:** Total Customers, Avg Recency, Avg Frequency, Avg Monetary, % High-Value Customers  
- **Charts:**  
  - Donut chart — Customer Distribution by Persona  
  - Bar chart — Revenue Contribution by Persona  
  - Scatter plot — Frequency vs Monetary (“Customer Behavior Map”)  
  - Summary Table — Revenue Share %, Avg Recency, Avg Frequency, Avg Monetary  
- **Interactive Filters:**  
  - Persona Dropdown  
  - Cluster Slider  
  - Monetary Tier Slicer (Low / Mid / High spend levels)  
- **Theme:** Elegant maroon–beige–gray color palette  
- **Interactivity:** All visuals respond dynamically to slicer selections  

**Key Insights:**  
- **Loyal Champions** dominate both customer base and total revenue.  
- **At-Risk Customers** show strong reactivation potential.  
- **Recent High Spenders** are emerging high-value customers to nurture further.  

---

## 👥 Key Personas  

| Persona | Characteristics | Suggested Strategy |
|----------|-----------------|--------------------|
| **Loyal Champions** | Frequent, high-value, recent buyers | Maintain loyalty through VIP programs and early access |
| **Recent High Spenders** | New and valuable customers | Encourage repeat purchases with personalized offers |
| **At-Risk Customers** | Previously active, now dormant | Reactivation campaigns with targeted discounts |
| **Occasional Buyers** | Moderate frequency, low spend | Promote with tailored product recommendations |

---

## 📈 Insights  
- Segmented customers into **4 actionable personas** using RFM + KMeans  
- Built an **interactive Power BI dashboard** for dynamic persona exploration  
- Identified *At-Risk* and *Recent High Spenders* as high-potential growth segments  
- Proposed data-backed strategies estimated to improve engagement by **~12% QoQ**

---

## 📂 Files in This Repository  

| File | Description |
|------|--------------|
| `customer_segmentation.ipynb` | Main analysis notebook (Python) |
| `Customer_Segmentation_Output.xlsx` | Final RFM dataset with cluster & persona labels |
| `Persona_RFM_Summary.html` | Interactive Plotly dashboard |
| `Customer_Segmentation_Dashboard.pbix` | **Power BI interactive dashboard** |
| `README.md` | Project documentation |

---

## 🚀 How to Run  

1. **Clone this repository**
   ```bash
   git clone https://github.com/Appu-Anand/Customer-Segmentation-and-Persona-Strategy.git
   cd Customer-Segmentation-and-Persona-Strategy
   
2. **Run the Python notebook**
    jupyter notebook customer_segmentation.ipynb
3.**Open the Power BI dashboard**
   Launch Power BI Desktop
   Open Customer_Segmentation_Dashboard.pbix
   Check that the file path links correctly to Customer_Segmentation_Output.xlsx
   
**🌟 Deliverables**

✅ Python Analytics Notebook – RFM segmentation + KMeans clustering
✅ Excel Dataset – Final labeled customer personas
✅ Power BI Dashboard – Interactive executive visualization
✅ Business Recommendations – Persona-specific engagement strategy

**🧩 Tech Stack**

Python: pandas, numpy, scikit-learn, matplotlib, seaborn, plotly

BI Tool: Microsoft Power BI

Data Source: Online retail transactional dataset (Excel/CSV)

**🧠 Key Learning**

Translating machine learning output into business-ready personas

Integrating Python analytics → Power BI storytelling

Designing dashboards aligned with executive decision-making

    
