# 📊 Online Retail Analysis | Power BI Dashboard

## 📌 Project Overview
This project presents an end-to-end **E-Commerce Business Intelligence Dashboard** built using the **UCI Online Retail II dataset**. The dashboard provides insights into **sales performance, customer segmentation, and transaction-level analysis** to support data-driven decision-making.

The solution includes **three interactive dashboard pages**:
- Sales Performance Overview  
- Customer Intelligence & Segmentation  
- Detailed Transaction Analysis  

---

## 📂 Dataset
**UCI Online Retail II Dataset**  
https://archive.ics.uci.edu/dataset/502/online+retail+ii

The dataset contains transactional data including:
- Invoice Number  
- Customer ID  
- Product Description  
- Quantity  
- Price  
- Invoice Date  
- Country  

---

# 📊 Dashboard Pages

## 1️⃣ Sales Performance Overview
This page provides high-level business insights.

### Visuals Included
- Total Revenue KPI  
- Total Orders KPI  
- Total Customers KPI  
- Average Order Value (AOV)  
- Monthly Sales & Orders Trend  
- Revenue by Country (Map)  
- Top 10 Products by Revenue  
- Orders by Day of Week  

### Key Insights
- Sales peak during end-of-year months  
- A small number of products drive major revenue  
- Most orders occur mid-week  
- Revenue distribution varies by country  

---

## 2️⃣ Customer Intelligence & Segmentation
This page focuses on customer behavior using **RFM analysis**.

### RFM Metrics
- Recency – Days since last purchase  
- Frequency – Number of purchases  
- Monetary – Total spending  

### Customer Segments
- Champions  
- Loyal Customers  
- Potential Loyalists  
- At Risk  
- Lost  

### Visuals Included
- Customer Segment Distribution  
- Customer Activity by Recency  
- Customer Churn Distribution  
- Customer Value Analysis (RFM Scatter Plot)  

### Key Insights
- Loyal customers contribute major revenue  
- A significant portion of customers are at risk  
- High-value customers cluster at low recency  
- Customer churn opportunities identified  

---

## 3️⃣ Detailed Transaction Analysis
This page provides granular transaction-level data.

### Visuals Included
- Interactive transaction table  
- Invoice details  
- Customer information  
- Product description  
- Quantity and price  
- Total price  
- Transaction type  

### Features
- Filtering by customer and country  
- Conditional formatting for revenue  
- Drill-down transaction analysis  

---

# ⚙️ Data Preparation
The following preprocessing steps were performed:

- Removed cancelled transactions  
- Removed negative quantities  
- Handled missing Customer IDs  
- Created TotalPrice column  
- Extracted Year, Month, Day, Hour  
- Created Month sorting columns  
- Created Transaction Type categories  

---

# 🧠 Calculated Measures

## Core Measures
- Total Revenue  
- Total Orders  
- Total Customers  
- Average Order Value  

## Customer Metrics
- Recency  
- Frequency  
- Monetary  
- Customer Segments  

---

# 🎨 Dashboard Features
- Interactive filtering  
- Cross-filtering between visuals  
- Conditional formatting  
- KPI cards  
- Geographic mapping  
- RFM segmentation  
- Time-series analysis  

---

# 🛠 Tools Used
- Power BI  
- DAX  
- Data Modeling  
- RFM Analysis  
- Data Cleaning  
- Business Intelligence Design  

---

# 📈 Business Value
This dashboard helps stakeholders:

- Monitor sales performance  
- Identify high-value customers  
- Detect churn risk  
- Analyze product performance  
- Understand purchase behavior  
- Explore transaction-level data  

---

# 📸 Dashboard Preview

- Sales Overview Page
- <img width="1299" height="733" alt="OnlineRetail 1" src="https://github.com/user-attachments/assets/a52e77c6-0ddb-481f-b4c2-161b5fd40de2" />

- Customer Intelligence Page
- <img width="1286" height="724" alt="OnlineRetail2" src="https://github.com/user-attachments/assets/ff93b297-9286-4cd5-9c53-2d378c16348b" />
 
- Detailed Transaction Page
- <img width="1287" height="724" alt="OnlineRetail3" src="https://github.com/user-attachments/assets/8926ba12-3f3b-4d52-9557-0d7e7eb992fa" />


---

# 🚀 How to Use
1. Download the `.pbix` file  
2. Open in Power BI Desktop  
3. Interact using slicers and filters  
4. Navigate across dashboard pages  

---

# 👤 Author
**Aravind Teja Bastipadu**  
Data Analyst | Power BI | SQL | Python | Data Visualization  

