# 🛒 A Case Study on DMart

## 📌 Overview

This project explores how DMart, a leading Indian retail chain, can optimize its real-time inventory using data analytics. The case study covers end-to-end steps from data cleaning and analysis to dashboard creation and insights extraction.

---

## 📂 Project Structure
```
├── data/
│ ├── raw_inventory_data.csv
│ ├── cleaned_inventory_data.csv
│
├── notebooks/
│ ├── inventory_analysis.ipynb
│
├── visuals/
│ ├── dmart_dashboard.pbix
│ ├── screenshots/
│ ├── dashboard_overview.png
│ ├── category_analysis.png
│ ├── stock_risk_analysis.png
│
```
---
![Dashboard Overview](./visuals/screenshots/dashboard_overview.png)

## 📹 Dashboard Walkthrough Video

[Dashboard video](https://github.com/khushal728/Dmart_Case_Study/issues/1#issue-3099881474)

---
## 🎯 Objective

To identify inefficiencies in inventory management and suggest actionable solutions to:
- Reduce stockouts
- Minimize excess inventory
- Improve sell-through and turnover rates
- Optimize category-wise inventory performance

---

## 🧹 Data Cleaning

- Tool Used: **OpenRefine**
- Actions Performed:
  - Removed nulls and duplicates
  - Standardized product categories
  - Merged city-level data for consistency

---

## 📊 Data Analysis

- Tool Used: **Python (Google Colab)**
- Libraries: `pandas`, `matplotlib`, `seaborn`

### KPIs Calculated:
- Total Sales
- Total Quantity Sold
- Average Basket Size
- Inventory Turnover Ratio
- Sell-Through Rate
- Repeat Customer Rate
- ABC Classification

---

## 📈 Dashboard

- Tool: **Power BI**
- Name: `DMart_Inventory_Optimization.pbix`

### Key Features:
- **KPI Cards** for Sales, Quantity, Products, Customers
- **Bar & Pie Charts** for Category-Wise Sales and Quantity
- **Risk Analysis**:
  - *Stockouts:* Grocery, Clothing, Footwear
  - *Overstock:* Stationery, Electronics
- **Top Cities and SKUs** visualized for demand planning
- **ABC Analysis** for identifying critical SKUs

---

## 📌 Key Insights

| Metric                    | Value               |
|--------------------------|---------------------|
| Total Sales              | ₹7.65 Crores        |
| Total Quantity Sold      | 9.6 Lakhs+ items    |
| Unique Products          | 1,016 SKUs          |
| Repeat Customer Rate     | 72%                 |
| Avg. Basket Size         | 3 items             |
| Top Selling Category     | Beauty & Hygiene    |
| Top Revenue Category     | Home & Kitchen      |

---

## 🧠 Recommendations

1. **Optimize reorder strategy** for high-risk categories.
2. **Offer bundled discounts** for overstocked items.
3. **Enhance demand forecasting** using ML models.
4. **Implement just-in-time inventory** for fast-moving goods.

---

## 📚 Learnings

- Hands-on with real-time retail inventory metrics
- Power BI DAX calculations for business KPIs
- Practical ABC Classification
- Importance of data storytelling

---

## 📬 Contact

For feedback or collaboration:

**Khushal [@khushal728](https://github.com/khushal728)**  


---

## 🔖 Tags

`Power BI` `Retail Analytics` `Inventory Management` `Supply Chain Optimization` `ABC Classification` `Data Storytelling` `Python` `OpenRefine`














