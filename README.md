# 🚲 Bike Sales Analysis — Excel End-to-End Project

## 📌 Business Problem
A bike retail company wanted to understand **what type of customer is most likely to purchase a bike** — based on demographics like income, age, commute distance, region, occupation, and marital status.

The goal was to clean the raw customer data, analyse purchase patterns, and build an interactive dashboard that allows stakeholders to filter and explore insights visually.

---

## 🛠️ Tools & Skills Used

| Tool | What I Did |
|---|---|
| **Excel** | Full end-to-end project — cleaning, analysis, and dashboard |
| **Data Cleaning** | Removed duplicates, standardized values, created age brackets |
| **Pivot Tables** | Summarized data by income, age, commute distance and region |
| **Charts & Visualizations** | Built bar charts and line graphs from pivot table data |
| **Interactive Dashboard** | Combined all visuals with slicers for dynamic filtering |

---

## 🗂️ Workbook Structure

The Excel file contains **4 sheets:**

| Sheet | Description |
|---|---|
| `bike_buyers` | Original raw dataset (1,000 customer records) |
| `Working Sheet` | Cleaned version of the data used for analysis |
| `Pivot Table` | All pivot tables summarizing key metrics |
| `Dashboard` | Final interactive dashboard with slicers |

---

## 🧹 Data Cleaning Steps

- **Removed duplicate records** to ensure each customer appears once
- **Standardized Marital Status** — changed `M` → `Married`, `S` → `Single` for readability
- **Standardized Gender** — changed `M` → `Male`, `F` → `Female`
- **Created Age Brackets** using a nested IF formula to group customers into:
  - `Adolescent` (under 31)
  - `Middle Age` (31–54)
  - `Old` (55+)
- Checked all columns for inconsistencies before building pivot tables

---

## 📊 Analysis & Key Insights

### 💰 Income vs. Bike Purchase
- **Male customers who purchased a bike** had a higher average income than those who didn't
- **Female customers** followed the same pattern — higher income correlated with bike purchases
- 💡 *Income is a strong indicator of purchase likelihood*

### 🚗 Commute Distance vs. Bike Purchase
- Customers with **0–1 mile commutes** purchased bikes the most
- Purchase rates dropped significantly for commutes **over 5 miles**
- 💡 *Short-distance commuters are the primary target market*

### 👶 Age Bracket vs. Bike Purchase
- **Middle Age customers (31–54)** had the highest bike purchase rate
- Adolescents and older customers purchased significantly less
- 💡 *Marketing campaigns should focus on the 31–54 age group*

### 🌍 Regional Breakdown
- Data covers customers from **Europe, North America, and Pacific** regions
- Dashboard slicers allow filtering by region to compare purchase behaviour

---

## 💡 Business Recommendations

1. **Target middle-aged customers (31–54)** with the highest income bracket — they are the most likely buyers
2. **Focus marketing on short-commute areas** — customers within 0–1 miles are the highest converters
3. **Male customers with above-average income** represent the most reliable buyer profile
4. **Reassess strategy for long-commute customers** — a different product or messaging may be needed

---

## 📁 Files in This Repository

| File | Description |
|---|---|
| `Bike_Sales.xlsx` | Full Excel workbook — raw data, cleaned data, pivot tables & dashboard |

> 💡 **Tip for recruiters:** Open the **Dashboard** sheet to see the interactive view with slicers. Use the **Pivot Table** sheet to explore the analysis.

---

## 👤 Author
**samueleziuzor11-dotcom**
Aspiring Data Analyst | Excel • SQL • Power BI • Power Pivot | Open to first role
