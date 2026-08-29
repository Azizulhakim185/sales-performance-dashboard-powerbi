# 📊 Sales & Profitability Dashboard — Power BI

An interactive Power BI dashboard analyzing sales, profit, and customer behavior across quarters, states, categories, and payment modes.

---

## 🎯 Objective

Turn raw transactional sales data into a single interactive view that lets a stakeholder slice performance by quarter and state, compare profit across sub-categories, and understand customer- and payment-mode-level patterns — all through cross-filtered visuals instead of static tables.

---

## 📁 Repository Contents

- **Power BI report (.pbix)** — the full report file, including data model, relationships, DAX measures, and report pages
- **Custom theme file** — a custom Power BI theme applied for consistent, presentation-ready styling
- **Order dataset** — order-level transactional data
- **Details dataset** — order line-item detail data, related to the Order table

## 🗂️ Dataset

Two related tables joined in the Power BI data model:

- **Order** — captures customer, state, category, sub-category, payment mode, and other order-level attributes
- **Details** — captures quantity, amount, and profit at the line-item level, linked back to Order

## 🧰 Tools & Techniques

- **Power BI Desktop** — data modeling, relationships, Power Query transformations
- **DAX** — calculated measures powering the KPI cards and aggregated visuals
- **Custom theme (JSON)** — consistent color palette and styling across all visuals
- **Interactive cross-filtering** via Quarter and State slicers

## 📈 Dashboard Features

- **4 KPI cards:** Total Amount · Total Quantity · Total Profit · Average Order Value
- **Profit by Month** — stacked column chart
- **Profit by Sub-Category** — stacked bar chart
- **Quantity by Payment Mode** — donut chart
- **Quantity by Category** — donut chart
- **Amount by State** — stacked bar chart
- **Amount by Customer Name** — stacked column chart
- Dashboard-wide filtering by **Quarter** (4 quarters) and **State**

## 💡 What This Dashboard Enables

- Spotting which quarters and states contribute most to overall profit
- Comparing profit performance across sub-categories to identify strong and weak segments
- Understanding customer payment preferences and category-level demand
- Identifying top customers and states by total sales contribution
- Drilling into monthly profit trends without leaving a single view

## 🚀 How to View

This is a native `.pbix` file, which requires **Power BI Desktop** (free) to open and interact with directly — including the slicers and cross-filtering.

## 🔮 Possible Next Steps

- Add year-over-year comparison as more periods become available
- Publish to Power BI Service for a shareable, browser-based interactive link
- Add a drill-through page for customer-level detail

---

## 📬 Connect

**Azizul Hakim (Aziz)**
[GitHub — Azizulhakim185](https://github.com/Azizulhakim185)
