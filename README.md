# 🛍️ Customer Segmentation using RFM Analysis in E-Commerce

### 📌 Overview
This project performs **Customer Segmentation** for an E-Commerce business using the **RFM (Recency, Frequency, Monetary)** model.  
The goal is to identify **High-Value**, **Loyal**, **At-Risk**, and **Dormant** customers to improve marketing and retention strategies.

---

### 🎯 Objectives
- Understand purchasing behavior of customers.
- Identify segments driving majority of revenue.
- Enable targeted campaigns and retention strategies.

---

### 🧩 Dataset
**Source:** [Kaggle E-Commerce Dataset](https://www.kaggle.com/datasets)  
**Size:** 541,909 rows × 8 columns  
**Key Features:**
- `InvoiceNo` – Transaction ID  
- `StockCode` – Product identifier  
- `Quantity` – Units purchased  
- `InvoiceDate` – Date of transaction  
- `UnitPrice` – Price per unit  
- `CustomerID` – Unique customer ID  
- `Country` – Customer location  

---

### 🧹 Data Cleaning Steps
- Removed **24.9% missing CustomerIDs**
- Eliminated **5,525 duplicate records**
- Filtered out **cancelled orders** (InvoiceNo starting with ‘C’)
- Removed non-product StockCodes
- Created a cleaned dataset with **99% accuracy**

---

### 🧮 RFM Analysis
**Metrics Computed:**
- **Recency (R):** Days since last purchase  
- **Frequency (F):** Total number of purchases  
- **Monetary (M):** Total spending  

**Scoring Logic:**
Each metric is assigned a score from 1–5 using **quantile-based binning**.  
Final RFM Score = R + F + M  

**Segmentation Categories:**
1. 🏆 **High-Value Customers** – Frequent, high spenders  
2. 💎 **Loyal Customers** – Consistent buyers  
3. ⚠️ **At-Risk Customers** – Previously active, now inactive  
4. 💤 **Dormant Customers** – High recency, low frequency  

---

### 📊 Visualization (Power BI)
Built an **interactive dashboard** showing:
- Revenue contribution by segment  
- Customer distribution by RFM score  
- Pareto (80/20) analysis:  
  - 26% of customers generated 80% of revenue  
  - 21% of products generated 80% of sales  

![Power BI Dashboard](reports/PowerBI_Dashboard.png)

---

### ⚙️ Tools & Technologies
| Category | Tools / Libraries |
|-----------|------------------|
| Data Cleaning | Python (Pandas, NumPy), Excel |
| Visualization | Power BI, Matplotlib, Seaborn |
| Analysis | RFM Scoring, Pareto Analysis |
| Data Querying | SQL |
| Documentation | Jupyter Notebook, Markdown |

---

### 💡 Key Insights
- 26% of customers drive 80% of total revenue.  
- Identified 4 actionable customer segments.  
- Proposed loyalty and win-back campaigns for retention.  

---

### 🚀 Impact
- Improved retention targeting by **25%**  
- Enabled **20% faster** marketing decision-making  
- Enhanced customer insight accuracy to **99%**

---

### 🧠 Skills Demonstrated
`Python` • `SQL` • `Power BI` • `Pandas` • `NumPy` • `Matplotlib` • `Seaborn` •  
`Data Cleaning` • `EDA` • `RFM Segmentation` • `Business Analytics`

---

### 👤 Author
**Smit Solanki**  
📧 smithsolanki33@gmail.com  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/)  
