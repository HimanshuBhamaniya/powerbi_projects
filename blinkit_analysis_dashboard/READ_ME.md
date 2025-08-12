# 🛒 Blinkit Analysis Dashboard

Welcome to the Blinkit Analysis Dashboard! This Power BI project dives deep into Blinkit's grocery data to uncover insights on sales performance, customer satisfaction, and outlet distribution. Whether you're into data storytelling or just curious about how fat content affects sales—this dashboard has something for you.

---

## 📁 Folder Structure

blinkit_analysis_dashboard/  
                           ├── BlinkIT Grocery Data.xlsx # Raw dataset used for analysis 
                           ├── blinkit_dashboard.pbix # Power BI dashboard file 
                           ├── icons/ # Icons used in the dashboard 
                           ├── images/ # Screenshots of the dashboard 
                           └── README.md # You're here!


---

## 🚀 Project Workflow

Here’s how the dashboard came to life:

1. **Requirement Gathering** – Defined business goals and KPIs.
2. **Data Walkthrough** – Explored the Excel file to understand the structure.
3. **Data Connection** – Imported the data into Power BI via Excel.
4. **Data Cleaning** – 
   - Standardized `Fat Content` values: `LF`, `low fat` → `Low Fat`; `reg`, `regular` → `Regular`
   - Left missing `Item Weight` values untouched (not used in analysis).
5. **Data Modeling** – Ensured relationships and data types were correctly set.
6. **Data Processing** – Applied transformations in Power Query.
7. **DAX Calculations** – Created measures for KPIs like Total Sales, Average Sales, etc.
8. **Dashboard Layouting** – Designed a clean, intuitive layout.
9. **Chart Development** – Built visuals based on business requirements.
10. **Report Development** – Finalized dashboard with interactivity and polish.
11. **Insights Generation** – Interpreted trends and patterns from the visuals.

---

## 📊 Business Requirements

The goal was to analyze Blinkit's performance across multiple dimensions using KPIs and charts:

### 🔑 KPI Metrics

- **Total Sales** – Overall revenue from all items sold
- **Average Sales** – Revenue per sale
- **Number of Items** – Count of unique items sold
- **Average Rating** – Customer satisfaction score

---

## 📈 Chart Requirements

| Chart Title                          | Objective                                                  | Chart Type         |
|-------------------------------------|-------------------------------------------------------------|--------------------|
| Total Sales by Fat Content          | Impact of fat content on sales + other KPIs                 | Donut Chart        |
| Total Sales by Item Type            | Performance of different item categories                    | Bar Chart          |
| Fat Content by Outlet for Sales     | Compare sales across outlets segmented by fat content       | Stacked Column     |
| Sales by Outlet Establishment Year  | Influence of outlet age/type on sales                       | Line Chart         |
| Sales by Outlet Size                | Correlation between outlet size and sales                   | Donut / Pie Chart  |
| Sales by Outlet Location            | Geographic distribution of sales                            | Funnel Map         |
| All Metrics by Outlet Type          | Breakdown of all KPIs by outlet type                        | Matrix Card        |

---

## 📦 Dataset Overview

- **Rows:** 8,523
- **Columns:**
  - `Item Fat Content`, `Item Identifier`, `Item Type`, `Outlet Establishment Year`, `Outlet Identifier`, `Outlet Location Type`, `Outlet Size`, `Outlet Type`, `Item Visibility`, `Item Weight`, `Sales`, `Rating`
- **Note:** Only `Item Weight` had missing values, which were not used in analysis.

---

## 🖼️ Dashboard Preview

Check out the screenshots in the `images/` folder to see the dashboard in action!  
Icons used for visual polish are stored in the `icons/` folder.

---

## 💡 Insights & Takeaways

- Low Fat items had higher sales volume across most outlets.
- Certain outlet types consistently outperformed others in both sales and ratings.
- Item Type and Outlet Size showed strong correlation with total sales.

---

## 🙌 Final Thoughts

This project was a great exercise in end-to-end dashboard development—from raw data to polished insights. If you're into Power BI, data cleaning, or just love a good donut chart, feel free to explore the repo and share feedback!

---

