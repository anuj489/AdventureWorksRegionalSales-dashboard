# 🌍 Adventure Works Regional Analysis Dashboard (Power BI)

This project presents an interactive **Power BI dashboard** to analyze **regional sales performance, profitability, and product trends** across different markets.  
It leverages **time intelligence, DAX measures, and geographical insights** to uncover business opportunities and track performance across Internet and Reseller channels.

📊 **Live Dashboard:**  
👉 [Click here to view in Power BI Service](https://app.powerbi.com/reportEmbed?reportId=974ee9d9-446c-484c-b78f-bb50813f18cc&autoAuth=true&ctid=e1d99821-ef38-4f48-836f-7a7ca113dab7)

---

## 📌 Project Overview  

The Power BI report is built using a **structured data modeling approach** that includes:  

- **Data Cleaning & Preparation:** Handled in Power BI with relationships across Sales, Products, Geography, and Date tables.  
- **Data Modeling:** Implemented a **Star Schema** with fact and dimension tables.  
- **Measures and KPIs:** Created multiple **DAX measures** for sales, cost, gross profit, and margin analysis.  
- **Time Intelligence:** Year-over-Year comparisons (CY vs PY).  
- **Channel Comparison:** Internet Sales vs Reseller Sales profitability.  

---

## 📊 Key Dashboard Sections  

### 📍 Page 1: KPI Overview & Trends  
- Total Sales, Total Cost, Gross Profit, and Gross Profit %  
- Internet vs Reseller Sales comparison  
- Sales distribution by Country & State (map visualization)  
- Year-over-Year Sales and Profit Trends  

### 📍 Page 2: Detailed Analysis  
- Sales, Cost, Margin by **Country and State/Province**  
- Drilldown into **Product Categories & Subcategories**  
- % Gross Profit and % Margin comparisons  

---
## 🧮 Measures Created  

The following DAX measures were created to support KPIs and visualizations in the Adventure Works Regional Analysis report:  

- **% Gross Profit** – Gross Profit % across all channels  
- **% Margin IS** – Internet Sales margin %  
- **% Margin RS** – Reseller Sales margin %  
- **Gross Profit** – Total Sales – Total Cost  
- **Margin IS** – Internet Sales margin (Sales – Cost)  
- **Margin RS** – Reseller Sales margin (Sales – Cost)  
- **Total Cost** – Overall cost  
- **Total Cost IS** – Internet Sales cost  
- **Total Cost RS** – Reseller Sales cost  
- **Total IS CY** – Internet Sales (Current Year)  
- **Total IS PY** – Internet Sales (Previous Year)  
- **Total Qty RS** – Reseller Sales quantity  
- **Total Quantity IS** – Internet Sales quantity  
- **Total RS CY** – Reseller Sales (Current Year)  
- **Total RS PY** – Reseller Sales (Previous Year)  
- **Total Sales** – Overall sales value  
- **Total Sales PY** – Total Sales (Previous Year)  



## 🎯 Business Value  

- Identify **top-performing regions and products**  
- Compare **Internet vs Reseller channels**  
- Analyze **year-over-year growth trends**  
- Discover **geographic hotspots** for sales  
- Evaluate **profitability at multiple levels** (country, state, product)  

---

## 🛠 Tools & Technologies  

- **Power BI Desktop / Service**  
- **Adventure Works DW (Sample Dataset)**  
- **DAX (Data Analysis Expressions)**  
- **Star Schema Modeling**  
- **Power Query for ETL**  

---
---

🔗 **Additional References**

- Mentor: [Divakar Kushwaha (LinkedIn)](https://www.linkedin.com/in/divakar-kushwaha/)  
- Learning Platform: [Web Convoy Academy](https://webconvoyacademy.in/)

---

## 📷 Dashboard Preview  

### Page 1 – KPI Overview, Map & Trends  
<img width="1110" height="620" alt="image" src="https://github.com/user-attachments/assets/45ba2738-821e-4c9a-b859-77b2e3a0ecd4" />


### Page 2 – Regional & Product Breakdown  
<img width="1115" height="612" alt="image" src="https://github.com/user-attachments/assets/863c3328-7da0-46a7-b4ac-dcbe531bc054" />


---

## ✨ Future Enhancements  

- Add **forecasting models** for sales prediction  
- Include **customer segmentation** dashboards  
- Automate **data refresh** for real-time updates  
- Apply **Row-Level Security (RLS)** for restricted access  




