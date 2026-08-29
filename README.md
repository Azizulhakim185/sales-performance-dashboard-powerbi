# 📊 Sales & Profitability Dashboard — Power BI

An interactive Power BI dashboard analyzing sales, profit, and customer behavior across quarters, states, categories, and payment modes — built to answer a simple business question: **where is profit actually coming from, and where is it leaking?**

---

## 🎯 Objective

Retail/sales datasets are easy to summarize but hard to *interrogate*. This dashboard turns two raw transactional tables into a single interactive view that lets a stakeholder slice performance by quarter and state, spot which sub-categories drive (or drag down) profit, and see customer- and payment-mode-level patterns without touching a spreadsheet.

---

## 📁 Repository Contents

| File | Description |
|---|---|
| `*.pbix` | Main Power BI report file (data model, DAX measures, report pages) |
| `*_theme.json` | Custom Power BI theme used for consistent styling |
| `Order.csv` | Order-level transactional data |
| `Details.csv` | Order line-item / detail data, related to `Order` |
| `README.md` | This file |

## 🗂️ Dataset

Two related tables joined in the Power BI data model:

- **Order** — order/date, customer name, state, category, sub-category, payment mode, and related order attributes
- **Details** — line-item level detail (quantity, amount, profit) linked back to `Order`

> *Note: add a line here on where the dataset came from (public sample dataset, coursework, synthetic data, etc.) — this matters to anyone reviewing the repo.*

## 🧰 Tools & Techniques

- **Power BI Desktop** — data modeling, relationships, Power Query transformations
- **DAX** — calculated measures for KPIs and aggregations
- **Custom theme (JSON)** — consistent color palette and styling across visuals
- Interactive **cross-filtering** via Quarter and State slicers

## 📈 Dashboard Features

- **4 KPI cards:** Total Amount · Total Quantity · Total Profit · Average Order Value
- **Profit by Month** — stacked column chart
- **Profit by Sub-Category** — stacked bar chart
- **Quantity by Payment Mode** — donut chart
- **Quantity by Category** — donut chart
- **Amount by State** — stacked bar chart
- **Amount by Customer Name** — stacked column chart
- Dashboard-wide filtering by **Quarter** and **State**

## 💡 Key Insights

> *Add 2–3 concrete, numbers-based takeaways here — e.g. "Q3 accounted for X% of total profit" or "Two sub-categories drove nearly half of all losses." This is the section that shows analytical thinking, not just tool proficiency, and it's usually what a reviewer reads first.*

## 🖼️ Preview

*(Add 1–2 dashboard screenshots here, and a link to the video walkthrough once posted on LinkedIn.)*

## 🚀 How to View

This is a native `.pbix` file, which requires **Power BI Desktop** (free) to open and interact with directly.

Prefer a quicker look? See the screenshots above or the video walkthrough: **[LinkedIn link]**

## 🔮 Possible Next Steps

- Add year-over-year comparison once more periods are available
- Publish to Power BI Service for a shareable, browser-based interactive link
- Add a drill-through page for customer-level detail

---

## 📬 Connect

**Azizul Hakim (Aziz)**
[LinkedIn] · [GitHub — Azizulhakim185](https://github.com/Azizulhakim185)
