## 📘 Project Overview
The *Retail Pulse: BlinkIT Sales & Performance Analytics Dashboard* provides a 360° view of BlinkIT’s operational and sales performance.  
It enables management and stakeholders to explore key business KPIs — including sales, ratings, and item distribution through an *interactive Excel-based dashboard*.  
This project delivers actionable insights to optimize outlet performance, enhance customer satisfaction, and improve inventory strategies.



## 🎯 Business Requirement
To conduct a comprehensive analysis of *BlinkIT’s sales, customer satisfaction, and inventory distribution* using various KPIs and visualizations in Excel or Power BI.  
The goal is to identify key performance trends, analyze product categories, and optimize outlet-level performance.



## 📊 KPI Requirements

| KPI | Description |
|------|--------------|
| *Total Sales* | The overall revenue generated from all items sold |
| *Average Sales* | The average revenue per sale |
| *Number of Items* | The total count of distinct items sold |
| *Average Rating* | The mean customer satisfaction rating across items |

---

## 📈 Chart & Visualization Requirements

| Visualization | Objective | Chart Type |
|----------------|------------|-------------|
| *Total Sales by Fat Content* | Analyze how fat content affects total sales and other KPIs | Donut Chart |
| *Total Sales by Item Type* | Identify which product categories perform best | Bar Chart |
| *Fat Content by Outlet (Sales)* | Compare total sales across outlets segmented by fat content | Stacked Column Chart |
| *Total Sales by Outlet Establishment Year* | Evaluate how outlet age/type influences total sales | Line Chart |
| *Sales by Outlet Size* | Analyze the correlation between outlet size and total sales | Pie/Donut Chart |
| *Sales by Outlet Location* | Assess the geographic distribution of sales | Funnel/Bar Chart |
| *All Metrics by Outlet Type* | Provide an overview of all KPIs broken down by outlet type | Matrix Card |



## 🧮 Data Source
The dataset contains transactional and outlet-level information from BlinkIT’s grocery sales records.  
It includes item details, outlet attributes, and sales performance metrics.

> *Data Origin:* Retail dataset inspired by BlinkIT sales data, similar to datasets available on Kaggle.



## 📑 Data Dictionary

| Column Name | Description |
|--------------|-------------|
| *Item_Identifier* | Unique ID for each product/item |
| *Item_Weight* | Weight of the item (in kilograms) |
| *Item_Fat_Content* | Fat classification of the item (Low Fat / Regular) |
| *Item_Visibility* | Percentage visibility of the item across stores |
| *Item_Type* | Category of the grocery item (e.g., Dairy, Snacks, Frozen Foods) |
| *Outlet_Identifier* | Unique ID for each store/outlet |
| *Outlet_Establishment_Year* | Year when the outlet was established |
| *Outlet_Size* | Size category of the outlet (Small / Medium / High) |
| *Outlet_Location_Type* | Tier classification of outlet location (Tier 1, Tier 2, Tier 3) |
| *Outlet_Type* | Type of store (e.g., Supermarket Type1, Grocery Store, etc.) |
| *Sales* | Total sales revenue generated for that item in that outlet |
| *Rating* | Average customer satisfaction rating (if applicable) |



## 🧰 Tools and Technologies Used
| Tool | Purpose |
|------|----------|
| *Microsoft Excel* | Data cleaning, transformation, and visualization |
| *Pivot Tables* | KPI summarization and grouping by outlet attributes |
| *Slicers* | Interactive filtering for Item Type, Outlet Size, and Location |
| *Charts & KPIs* | Visual representation of business performance |
| *Conditional Formatting* | Highlighting performance metrics and trends |



## ⚙️ Methodology / Steps Followed
1. *Requirement Gathering:* Collected business goals and KPIs from stakeholders.  
2. *Stakeholder Identification:* Determined decision-makers and dashboard users.  
3. *Data Cleaning:* Removed inconsistencies, duplicates, and standardized fields.  
4. *Data Processing:* Added calculated columns and custom metrics (e.g., Average Sales, Ratings).  
5. *Data Analysis:* Used pivot tables and Excel functions for trend identification.  
6. *Visualization:* Built charts, KPIs, and slicers for interactivity.  
7. *Dashboard Creation:* Designed and formatted a cohesive, interactive dashboard layout.



## 🤖 Analytical Techniques
This is a *descriptive analytics* project focusing on sales and performance insights.  
The key techniques used include:
- *Descriptive Analysis:* Summarizing key sales and outlet metrics.  
- *Comparative Analysis:* Comparing KPIs across item types and outlet attributes.  
- *Trend Analysis:* Evaluating sales over years of establishment.  
- *Performance Segmentation:* Ranking outlets based on key sales KPIs.


## 📰Dashboard
<img width="1312" height="741" alt="Blinkit-Analysis-Dashboard" src="https://github.com/user-attachments/assets/6013009a-9926-48a4-9814-c669144d5233" />



## 🧠 Key Insights & Conclusion
- *Tier 3 outlets* recorded the highest total sales (~$472K).  
- *Regular fat products* dominate, contributing 65% of total sales.  
- *Medium-sized outlets* outperform smaller ones in both sales and average ratings.  
- Sales peaked during *2018–2019*, showing BlinkIT’s strongest growth phase.  
- *Top-performing categories:* Fruits & Vegetables, Snack Foods, and Household Items.  

➡️ The dashboard empowers decision-makers to monitor sales, identify trends, and improve outlet performance effectively.



## 💡 Business Impact
- Improved visibility into *sales performance and product trends*.  
- Enabled *data-driven inventory and pricing decisions*.  
- Identified high-performing outlets and product categories.  
- Enhanced management’s ability to track KPIs visually and interactively.



## 🔮 Future Scope & Recommendations
To enhance this analysis further, the following improvements can be considered:
1. *Integration with Power BI or Tableau* for advanced interactivity and live data refresh.  
2. *Predictive Modeling* to forecast future sales and identify potential growth outlets.  
3. *Customer Segmentation* using RFM (Recency, Frequency, Monetary) analysis.  
4. *Automated Dashboard Refresh* using Power Query or VBA scripts.  
5. *Data Expansion* by incorporating promotional, pricing, and demographic data for deeper insights.

