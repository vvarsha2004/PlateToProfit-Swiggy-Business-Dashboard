# PlateToProfit-Swiggy-Business-Dashboard
**An end-to-end interactive sales analytics dashboard built entirely in Microsoft Excel — covering ₹53.01M in food delivery transactions across cities, states, food types, and time periods.**

---

## 📌 Project Overview

This project analyzes **Swiggy food delivery data** using Microsoft Excel's advanced features — Power Query, Pivot Tables, dynamic charts, slicers, and conditional formatting — to build a fully interactive business intelligence dashboard.

---

## 📊 Key Metrics at a Glance

| Metric | Value |
|---|---|
| 💰 Total Sales | ₹ 53.01 Million |
| 🛒 Total Orders | 1,97,400 |
| ⭐ Average Rating | 4.34 / 5.00 |
| 🧾 Average Order Value | ₹ 268.51 |
| 📝 Total Rating Count | ₹ 5.59 Million |

---

## 🗂️ Dashboard Sections

### 1. 📈 Monthly Sales Trend (Jan – Aug)
- Line chart tracking revenue momentum across **8 months**
- Identifies seasonal peaks and dips in ordering behavior
- Supports month-level drill-down via order date slicer

### 2. 📅 Daily Sales Pattern
| Day | Revenue |
|-----|---------|
| Sunday | ₹ 7.6M |
| Monday | ₹ 7.4M |
| Tuesday | ₹ 7.4M |
| Wednesday | ₹ 7.5M |
| Thursday | ₹ 7.7M |
| Friday | ₹ 7.6M |
| **Saturday** | **₹ 7.8M** ← Peak |

> Saturday drives the **highest single-day revenue**, confirming weekend demand surge behavior.

---

### 3. 🥗 Sales by Food Type
| Category | Revenue | Share |
|----------|---------|-------|
| 🍖 Non-Vegetarian | ₹ 34.4M | ~65% |
| 🥦 Vegetarian | ₹ 18.7M | ~35% |

> Non-Veg orders significantly outperform Veg across all quarters.

---

### 4. 🗓️ Quarterly Performance Breakdown
| Quarter | Sales | Avg Rating | Orders |
|---------|-------|------------|--------|
| Q1 | ₹ 19.7M | 4.3 ⭐ | 73,100 |
| Q2 | ₹ 19.9M | 4.3 ⭐ | 74,200 |
| Q3 | ₹ 13.4M | 4.3 ⭐ | 50,200 |

> Q2 leads in both revenue and order volume. Q3 shows a **32.7% dip** — potential churn investigation point.

---

### 5. 🏙️ Top 5 Cities by Revenue
| Rank | City | Revenue |
|------|------|---------|
| 🥇 1 | Bengaluru | ₹ 5.46M |
| 🥈 2 | Lucknow | ₹ 3.12M |
| 🥉 3 | Hyderabad | ₹ 3.02M |
| 4 | Mumbai | ₹ 3.02M |
| 5 | New Delhi | ₹ 2.83M |

> Bengaluru dominates with **₹5.46M** — nearly **76% more** than the second-highest city (Lucknow).

---

### 6. 🗺️ State-Level Sales Heatmap
- India choropleth map with **color-intensity encoding** (₹0.6M → ₹3.0M → ₹5.5M scale)
- Visualizes geographic concentration of orders across states
- Built using Excel's **Bing Maps integration**

---

### 7. 📆 Weekly Sales Trend (Weeks 1 – 36)
- Bar chart covering **36 weeks** of order data
- Range: ₹0.00M → ₹2.00M per week
- Exposes micro-trends, promotional spikes, and low-demand windows

---

## 🛠️ Tools & Techniques Used

| Feature | Purpose |
|---------|---------|
| **Power Query** | Data cleaning, transformation, type casting |
| **Pivot Tables** | Aggregation by city, state, category, date |
| **Pivot Charts** | Dynamic bar, line, donut, and map visuals |
| **Slicers** | Interactive filter by Month, Category, Restaurant |
| **Conditional Formatting** | Heatmap cells in the quarterly table |
| **Donut Chart** | Veg vs Non-Veg food type split |
| **Bing Map Visual** | Geographic state-level distribution |
| **Named Ranges** | Cleaner formula management |
| **Data Validation** | Dropdown-based filter controls |

---

## 🎛️ Interactive Filters Available

- **Order Date** — Jan, Feb, Mar, Apr, May, Jun, Jul, Aug
- **Category** — Desi, Chinese, Pasta, Roll, Sides, and more
- **Restaurant** — Shiv Sagar, Shiv Sagar Veg, Shivansh Fast Food, Short Crust Cakes, and more

---

## 💡 Key Business Insights

- 📍 **Bengaluru** is the #1 revenue city at ₹5.46M — focus marketing efforts here
- 🗓️ **Q3 saw a 32.7% revenue drop** vs Q2 (₹13.4M vs ₹19.9M) — investigate churn cause
- 📅 **Saturdays consistently peak** — ideal window for promotions and flash deals
- 🥩 **Non-Veg items drive 65% of revenue** — prioritize Non-Veg restaurant partnerships
- ⭐ **Consistent 4.3 rating across all quarters** — stable service quality maintained
- 🏙️ **Top 5 cities account for ~34% of total revenue** (₹18.07M / ₹53.01M)

---
## 🏁 Conclusion

This Swiggy Excel Dashboard analyzes ₹53.01M in sales across 1,97,400 orders and reveals that Bengaluru leads revenue at ₹5.46M, Non-Veg dominates at 65%, and Saturdays are peak order days. Despite a 32.7% Q3 dip, customer ratings remained steady at 4.3 throughout. This project demonstrates that Microsoft Excel alone is capable of delivering powerful, interactive, business-ready insights — no external BI tool required.



---

