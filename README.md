# 📊 Business Sales Performance Analytics
### Future Intern — Data Science & Analytics Internship | Task 1

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=flat&logo=pandas)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat&logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)
![Internship](https://img.shields.io/badge/Future%20Intern-Task%201-blueviolet?style=flat)

---

## 📌 Project Overview

This project is the **first task** of the **Future Intern Data Science & Analytics Internship**.  
It performs a complete **Exploratory Data Analysis (EDA)** on a custom Superstore Management System dataset to uncover actionable business insights related to:

- Sales and profitability trends
- Category and regional performance
- Customer segment behavior
- Delivery and order fulfillment analysis
- Inventory and supplier insights

---

## 📁 Project Structure
```
Business-Sales-Performance-Analytics/
│
├── EDA_superstone.ipynb                 # Main Jupyter Notebook (Full EDA)
├── Superstore_Management_System.csv     # Source dataset (custom)
├── superstore_analysis_results.csv      # Exported analysis summary results
└── README.md                            # Project documentation
```

---

## 📂 Dataset Description

**File:** `Superstore_Management_System.csv` *(Custom Dataset)*  
**Total Records:** 1,000 Orders

| Column | Description |
|--------|-------------|
| Order ID, Order Date, Ship Date | Order tracking details |
| Customer ID, Name, Segment | Customer info — Consumer, Corporate, Home Office |
| Product ID, Name, Category | Product details — Grocery, Electronics, Furniture, Office Supplies |
| Region, State, City | Geographic data |
| Quantity, Unit Price, Discount (%) | Pricing and quantity |
| Sales Amount, Cost Price, Profit | Financial metrics |
| Payment Mode | Payment method used |
| Delivery Status | Delivered, Pending, Returned, Cancelled |
| Supplier Name, Supplier Email | Supplier information |
| Stock Left, Auto Reorder, Reorder Quantity | Inventory management |

---

## 📊 Key Findings

| Metric | Value |
|--------|-------|
| 💰 Total Sales | $12,737,842.60 |
| 📈 Total Profit | $3,186,464.74 |
| 🛒 Total Orders | 1,000 |
| 📉 Avg. Profit Margin | 25.02% |
| 🏆 Top Category | Grocery ($846,039.25) |
| 🌍 Best Region | North |
| 👥 Best Customer Segment | Home Office |

---

## 🔍 Analysis Performed

1. **Sales & Profit Overview** — Total revenue, profit, order count, and margin analysis
2. **Category Performance** — Comparison across Grocery, Electronics, Furniture, Office Supplies
3. **Regional Analysis** — Sales and profit breakdown by North, South, East, West
4. **Customer Segment Analysis** — Revenue and profitability per segment
5. **Delivery Status Distribution** — Order fulfillment rate analysis
6. **Time Series Analysis** — Monthly/yearly sales trends and seasonality
7. **Discount Impact Analysis** — Effect of discounts on profit margins
8. **Inventory Insights** — Stock levels, reorder flags, supplier performance

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical computations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical plots
- **Jupyter Notebook** — Interactive development environment

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 🙌 Acknowledgements

- **Future Intern** — For providing this internship opportunity
- This dataset (`Superstore_Management_System.csv`) is an **original custom dataset** created specifically for this project

---

> ⭐ If you found this project helpful, please consider giving it a star!
