# Infosys Sales Performance Dashboard

## Table of Contents
1. Project Statement  
2. Objectives  
3. Project Timeline  
4. Tools and Technologies  
5. Project Scope  
6. Modules and Milestones  
7. Key Performance Indicators (KPIs)  
8. Visualizations and Insights  
9. DAX Calculations and Measures  
10. Future Improvements  
11. Project Deliverables  

---

## 1. Project Statement
Develop a Power BI-based Sales Performance Dashboard for Infosys to transform raw sales data into actionable insights. The dashboard will enable tracking of KPIs, dynamic reporting, and real-time monitoring of sales performance.

---

## 2. Objectives
- Design an interactive Power BI dashboard to visualize Infosys’ sales performance.  
- Facilitate tracking of KPIs like sales growth, customer segmentation, and product performance.  
- Enable drill-down analysis with filters for detailed insights.

---

## 3. Project Timeline
| Weeks  | Milestone                        | Description                            |
|--------|----------------------------------|----------------------------------------|
| 1–3    | Data Preparation and Cleaning   | Import, clean, and transform data.     |
| 4–6    | Basic Visualizations            | Develop initial charts and graphs.     |
| 7–8    | Advanced Sales Analysis         | Implement DAX measures and analytics.  |
| 9–10   | Dashboard Compilation           | Finalize and present the dashboard.    |

---

## 4. Tools and Technologies
- **Power BI**: For visualization and dashboard creation.  
- **Data Sources**: Excel, CSV files, and SQL databases.  
- **DAX**: For advanced calculations and measures.

---

## 5. Project Scope
- Integrate data from multiple sources.  
- Focus on metrics like total revenue, regional performance, and customer segmentation.  
- Provide interactive analytics through advanced Power BI features.

---

## 6. Modules and Milestones
### Milestone 1: Data Preparation (Weeks 1–3)
- Import data from Excel, CSV, and SQL.  
- Clean and transform data using Power Query.  
- Create relationships between tables.

### Milestone 2: Basic Visualizations (Weeks 4–6)
- Create visualizations like clustered column charts, line charts, and pie charts.

### Milestone 3: Advanced Sales Analysis (Weeks 7–8)
- Implement DAX measures (e.g., sales growth rate, gross profit margin).  
- Add slicers and advanced visuals like waterfall charts.

### Milestone 4: Final Dashboard (Weeks 9–10)
- Compile visuals into an interactive dashboard.  
- Add tooltips, bookmarks, and navigation features.

---

## 7. Key Performance Indicators (KPIs)
- Total Sales  
- Sales Growth Rate  
- Regional Sales Breakdown  
- Product Category Performance  
- Customer Acquisition  

---

## 8. Visualizations and Insights
- **Clustered Bar Chart**: Sales by region.  
- **Line Chart**: Sales trends over time.  
- **Waterfall Chart**: Contributions to sales.  
- **Bar Chart**: Top-performing cities and products.  
- **Gauge Chart**: Sales target progress.

---

## 9. DAX Calculations and Measures
- **Total Sales**: `SUM(Sales[SalesAmount])`  
- **Gross Profit**: `[Total Sales] - [Total Cost]`  
- **Profit Percentage**: `DIVIDE([Gross Profit], [Total Sales])`  
- **Sales Growth %**: `DIVIDE([Total Sales] - [Previous Year Sales], [Previous Year Sales])`  
- **Top 10 Customers**: `TOPN(10, Sales, [Total Sales])`  

---

## 10. Future Improvements
- Incorporate predictive analytics for sales forecasting.  
- Enable real-time data updates.  
- Enhance customer segmentation with advanced metrics.

---

## 11. Project Deliverables
- Structured and cleaned data.  
- Interactive Power BI dashboard.  
- Detailed presentation of insights and recommendations.
