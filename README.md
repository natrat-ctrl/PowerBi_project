# 📊 Power BI — Data Analysis & Visualization
### Internet Sales Dashboard | School Project

![Dashboard Preview](dashboard_preview.png)

> **Myyntitilastot aikavälillä 29.12.2010 – 28.01.2014**

---

## 🗂️ Project Overview

An interactive sales analytics dashboard built in **Power BI Desktop**, combining three relational data sources to uncover customer behavior, geographic sales patterns, and revenue trends across 2011–2014.

---

## 🗃️ Data Sources

| Table | Description |
|---|---|
| `FactInternetSales` | Transactional sales data — order dates, amounts, quantities |
| `DimCustomer` | Customer demographics — gender, occupation, number of children |
| `DimGeography` | Geographic data — country, state/province for spatial analysis |

---

## 📈 Visualizations & Analysis

### 1. Children at Home and Gender *(Clustered Bar Chart)*
Breaks down total sales by number of children at home, segmented by gender (F/M). Customers with **0 children generate the highest sales volume** (~8–9M€), with a clear drop-off as family size increases.

### 2. Sum of Sales Amount by EnglishOccupation *(Donut Chart)*
**Professionals (33.75%)** are the top-spending segment, followed by Skilled Manual (21.94%), Management (18.62%), Clerical (15.96%), and Manual (9.73%). Key insight for targeted marketing.

### 3. State Province Name *(Map Visual)*
Interactive geographic map showing sales concentration by region. Sales are heavily concentrated in **North America**, enabling quick identification of top-performing markets.

### 4. Sum of Sales Amount by Year, Quarter, Month and Day *(Line Chart)*
Time series from Jan 2011 to Jan 2014 with drill-down capability (Year → Quarter → Month → Day). Shows a clear **upward trend** peaking in late 2013.

### 5. AverageAmount *(KPI Card)*
Displays the average transaction value: **486.09€** — a key metric for understanding customer purchase behavior.

### 6. MenWithZeroChildren *(KPI Card)*
Custom DAX measure showing total sales from male customers with no children: **8.90M€** — the single largest customer segment.

### 7. Tavoite / Goal *(Gauge Chart)*
Tracks cumulative sales against a **40M€ target**. Current result: **29.36M€** (~73% attainment) — clear KPI for management reporting.

---

## 🎛️ Interactivity — Slicers & Filters

All visuals are fully cross-filtered. Selecting any value instantly updates the entire dashboard:

| Slicer | Function |
|---|---|
| **Gender** | Filter by Female / Male customers |
| **EnglishOccupation** | Drill into specific job categories |
| **CountryRegionCode** | Focus on specific markets |
| **OrderDate** | Adjust time window with a range slider |

---

## 🛠️ Skills Demonstrated

- ✅ Data modeling with star schema (Fact + Dimension tables)
- ✅ Custom DAX measures (AverageAmount, MenWithZeroChildren)
- ✅ Cross-filtering and slicer interactivity
- ✅ Multiple visualization types (bar, donut, map, line, gauge, KPI cards)
- ✅ Drill-down time intelligence (Year → Quarter → Month → Day)
- ✅ Multi-page report layout
- ✅ Finnish-language title and localized formatting
- ✅ UX-focused dashboard design for business stakeholders

---

## 📁 Project Structure

```
PowerBI_luento1/
│
├── PowerBI_project.pbix       # Power BI project file
├── dashboard_preview.png      # Dashboard screenshot
└── README.md                  # This file
```

---

## 🚀 How to Open

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Clone or download this repository
3. Open `PowerBI_luento1.pbix` in Power BI Desktop
4. Explore the dashboard — use the slicers to filter data interactively

---
