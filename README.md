# 📊 AdventureWorks Internet Sales Analytics Dashboard

### 🔍 Project Overview
The **AdventureWorks Internet Sales Analytics Dashboard** is an interactive Power BI solution designed to provide deep insights into sales, profitability, customer behavior, and product performance across multiple dimensions.  
This project demonstrates advanced data modeling, DAX measures, and visual storytelling to support business decision-making through a dynamic and professional dashboard interface.

---

### 🧠 Objectives
- Track and visualize **total sales, profit, and return performance** across time and regions.  
- Analyze **customer segmentation and retention patterns** to identify high-value groups.  
- Evaluate **product-level profitability** and understand return cost impacts.  
- Provide **executive-level KPIs** for quick strategic insights.

---

### 🧩 Data Model Structure

**Data Sources**
- `SalesData2020` – Transactional sales records  
- `ReturnData` – Returned item details  
- `CustomerInformation` – Demographic and behavioral data  
- `ProductInformation`, `ProductCategory`, `ProductSubCategory` – Product hierarchy and attributes  
- `TerritoryLookup` – Region and country mapping  
- `Calendar` – Time intelligence and period-based analysis  

**Relationships**
- Star schema with `SalesData2020` as the fact table  
- Dimension tables: `CustomerInformation`, `ProductInformation`, `TerritoryLookup`, `Calendar`  

---

### ⚙️ Key DAX Measures
- `Total Sales` = SUMX(SalesData, SalesData[OrderQuantity] * RELATED(ProductInformation[ProductPrice]))  
- `Total Profit` = [Total Sales] - [Total Cost]  
- `Profit Margin (%)` = DIVIDE([Total Profit], [Total Sales])  
- `Return Rate (%)` = DIVIDE([Total Units Returns], [Total Units Sold])  
- `YoY Growth`, `MoM Growth`, `YTD Sales`, `Customer Lifetime Value (CLV)`  
- Dynamic measures for **Target vs Actual**, **Retention**, and **Profit Impact**

---

### 🖥️ Dashboard Pages and Insights

#### 1. **Overview**
- Executive summary KPIs: Revenue, Profit, Orders, Return Rate  
- Year-over-Year and Month-over-Month performance overview  
- High-level visualization of sales and profitability trends  
![AdventureWorks Internet Sales Analytics_page-0001](https://github.com/user-attachments/assets/3ebbc329-47ed-4090-8463-b4abcf1e6dac)


#### 2. **Sales Performance**
- Time-series analysis of sales and orders  
- Product category contribution  
- Target vs Actual performance visualization  
![AdventureWorks Internet Sales Analytics_page-0002](https://github.com/user-attachments/assets/f425f27c-0854-4938-a9e4-4e1dd56df01f)


#### 3. **Customer Analytics**
- Total and active customers, new vs lost customer metrics  
- Top 10 customers by sales  
- Customer retention trend and behavior analysis
![AdventureWorks Internet Sales Analytics_page-0003](https://github.com/user-attachments/assets/0676546b-db93-452e-b8c7-1edb563f8756)


#### 4. **Product Profitability**
- Profit margin by product and category  
- Top and low-performing products  
- Profit per unit and product return impact  
![AdventureWorks Internet Sales Analytics_page-0004](https://github.com/user-attachments/assets/d198bdf2-18de-491b-9166-38a70be408ae)


#### 5. **Regional Insights**
- Sales and profit distribution by region and country  
- Map visualization for geographic performance  
- Top-performing markets  
![AdventureWorks Internet Sales Analytics_page-0005](https://github.com/user-attachments/assets/c2784783-ece1-411f-889f-355feda1b78f)


#### 6. **Returns Analysis**
- Total value of returns and profit loss impact  
- High-risk products and regions  
- Adjusted profit after return deduction  
![AdventureWorks Internet Sales Analytics_page-0006](https://github.com/user-attachments/assets/98be0da9-532a-4fcb-afd5-320518373daf)


#### 7. **Time Intelligence**
- Year-to-Date (YTD) and Month-to-Date (MTD) sales  
- YoY and MoM comparison charts  
- Seasonal sales and profit trend  
![AdventureWorks Internet Sales Analytics_page-0007](https://github.com/user-attachments/assets/9b612236-de37-4c03-82cc-2479f9bc6a18)


#### 8. **Customer Segmentation**
- CLV-based customer segmentation  
- RFM (Recency, Frequency, Monetary) pattern visualization  
- Cumulative sales distribution by customer rank  
![AdventureWorks Internet Sales Analytics_page-0008](https://github.com/user-attachments/assets/07aa2fc0-58a8-490b-b235-ebcccd87792c)


#### 9. **Product Profile**
- Drill-through page for product-level deep dive  
- Product cost, sales, profit margin, and return details  
![AdventureWorks Internet Sales Analytics_page-0009](https://github.com/user-attachments/assets/12584752-d1b5-4de6-98b1-a141a876e9d3)


---

### 🎨 Design and User Experience
- **Theme Color:** `#00AEB9` (Turquoise) with white-based minimalist layout  
- **Navigation Panel:** Left-side vertical panel with icons and text  
- **Consistency:** Uniform KPIs, typography, and formatting across all pages  
- **Accessibility:** Searchable slicers, interactive filters, and bookmarks for seamless navigation  

---

### 📈 Business Impact
- Enables stakeholders to identify high-profit regions and customer segments.  
- Provides actionable insights for reducing return rates and increasing profit margins.  
- Supports decision-making for inventory, marketing, and customer retention strategies.  

---

### 🧰 Tools & Technologies
- **Power BI Desktop**  
- **DAX (Data Analysis Expressions)**  
- **Power Query (ETL)**  
- **Star Schema Data Modeling**  
- **Azure Maps & Geo Visualization**

---

## 🙋‍♂️ About Me

I'm passionate about data, product thinking, and solving real-world problems with business intelligence. If you're interested in collaborating or want to discuss the dashboard, feel free to connect!

<img width="512" height="512" alt="portfolio" src="https://github.com/user-attachments/assets/8c747e78-eb98-4232-a211-751132f3498c" /> https://mdyeakub-py.github.io/Personal_Portfolio-/


🔗 https://www.linkedin.com/in/mdyeakub35/

📧 mdyeakub.cse@gmail.com

🐱 GitHub: https://github.com/MdYeakub-py

---

Thanks for checking out my iFlix Movie Streaming Analysis – Power BI Dashboard project! 🍽️📊
---

### 📎 License
This dashboard was created for educational and analytical purposes using the **AdventureWorks sample dataset** provided by Microsoft.  
All visualizations and measures were custom-developed for demonstration of BI best practices.

---

