# 🛒 E-Commerce Sales Analysis — 2024

> **Option 4** of the Data Analysis Project  
> A complete end-to-end analysis of 100 sales transactions across 5 products and 4 regions.

---

## 📁 Project Structure

```
ecommerce_analysis/
├── README.md                        ← You are here
├── analysis.ipynb                   ← Main Jupyter notebook
├── requirements.txt                 ← Python dependencies
│
├── data/
│   └── sales_data.csv               ← Raw dataset (100 rows, 7 columns)
│
├── visualizations/
│   ├── chart1_revenue_trends.png    ← Monthly trend line + stacked bar
│   ├── chart2_product_region.png    ← Donut chart + horizontal bar
│   └── chart3_scatter_heatmap.png   ← Scatter plot + product×region heatmap
│
└── report/
    └── insights_report.md           ← Written analysis & recommendations
```

---

## 📊 Dataset Overview

| Column       | Type    | Description                     |
|-------------|---------|--------------------------------|
| Date        | date    | Transaction date (Jan–Apr 2024) |
| Product     | string  | Phone, Laptop, Tablet, etc.     |
| Quantity    | int     | Units sold per transaction      |
| Price       | int     | Unit price in INR               |
| Customer_ID | string  | Unique customer identifier      |
| Region      | string  | East, West, North, South        |
| Total_Sales | int     | Quantity × Price                |

**100 transactions | 5 products | 4 regions | ₹12.37M total revenue**

---

## 🔍 Key Findings

1. **Laptops** are the top revenue driver at ₹3.89M (32% share)
2. **March 2024** was the peak month with ₹4.49M in sales
3. **North & South** regions dominate with 65% of total revenue
4. Price sweet spot: ₹15,000–₹40,000 with 3–8 units per order
5. **Tablets** show strong regional skew toward North

---

## 🚀 How to Run

```bash
# 1. Install dependencies
pip install -r requirements.txt

# 2. Launch the notebook
jupyter notebook analysis.ipynb
```

---

## 🛠️ Tech Stack

- **Python 3.12** — Core language
- **pandas** — Data loading, cleaning, aggregation
- **matplotlib** — All visualizations
- **numpy** — Numerical operations
- **Jupyter** — Interactive analysis environment
