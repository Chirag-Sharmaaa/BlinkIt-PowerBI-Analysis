# 🛒 Blinkit Sales Analysis (Power BI Dashboard)

This Power BI project performs a comprehensive sales performance analysis for **Blinkit**, India’s quick commerce platform. The dashboard was built as a practice project to showcase business intelligence skills and DAX capabilities using structured sales data.

---

## 📌 Note:

> This is a learning-oriented project inspired by a public YouTube tutorial by *Data Tutorials*. While the dataset is synthetic, the dashboard demonstrates real-world reporting use cases.

---

## 📷 Preview

![Blinkit Power BI Dashboard](images\Dashboard_image.png)

---

## 📌 Business Objectives

To identify trends, insights, and opportunities for optimization in:
- **Sales performance**
- **Customer satisfaction**
- **Inventory distribution**

---

## 📊 Key KPIs

1. **Total Sales** – Total revenue generated from all items  
2. **Average Sales** – Revenue per item  
3. **Number of Items** – Count of unique products sold  
4. **Average Rating** – Average customer rating for products

---

## 📈 Dashboard Visuals

| Chart | Purpose |
|-------|---------|
| **Donut Chart** | Total Sales by Fat Content |
| **Bar Chart** | Total Sales by Item Type |
| **Stacked Column Chart** | Fat Content by Outlet for Total Sales |
| **Line Chart** | Total Sales by Outlet Establishment Year |
| **Pie Chart** | Sales by Outlet Size |
| **Funnel Map** | Sales by Outlet Location |
| **Matrix Table** | All KPIs by Outlet Type |

---

## 🧮 Dataset Fields

Based on a structured CSV with columns:
- `Item Fat Content` (e.g. Low Fat, Regular)
- `Item Identifier`
- `Item Type` (e.g. Fruits, Dairy, Household)
- `Outlet Establishment Year`
- `Outlet Identifier`
- `Outlet Location Type` (e.g. Tier 1, 2, 3)
- `Outlet Size` (Small, Medium, High)
- `Outlet Type` (e.g. Supermarket Type1)
- `Item Visibility`, `Item Weight`, `Sales`, `Rating`

---

## 🧱 Steps Followed

- Business Requirement Gathering
- Data Cleaning & Quality Check
- Data Modeling
- Data Processing & DAX Calculations
- Dashboard Layout & Chart Formatting
- Insight Generation

---

## ⚙️ Tools Used

- **Power BI Desktop**
- **DAX** (for calculated KPIs and measures)
- **Excel/CSV** as data source


---
## 🔍 Insights & Key Findings

- 🟡 **Regular items** contributed more to total sales than low-fat items, but had a slightly lower average rating.
- 🏪 **Supermarket Type 1** outlets showed the highest total sales and hosted the majority of popular item categories.
- 🗓️ Outlets established between **2009 and 2012** generated maximum revenue, suggesting maturity and stability positively impact performance.
- 📦 **Fruits & Vegetables**, **Snack Foods**, and **Household** items were top-performing categories in both sales and item count.
- 🌍 **Tier 3 cities** had the highest sales, indicating increasing market penetration in semi-urban areas.

---

## ✅ Conclusion

This dashboard helped identify which product categories, outlet types, and locations drive the most revenue for Blinkit. It also provided valuable insights into customer preferences and operational patterns.

Such insights can help optimize inventory distribution, plan expansion strategies, and enhance customer satisfaction.
