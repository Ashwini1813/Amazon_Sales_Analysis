![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python)
![SQL](https://img.shields.io/badge/SQL-SQLite-orange?style=for-the-badge&logo=sqlite)
![Tableau](https://img.shields.io/badge/Tableau-Dashboard-blue?style=for-the-badge&logo=tableau)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)

# 🛒 Amazon Sales Analysis — SQL + Tableau Dashboard

## 📌 Overview
An end-to-end data analytics project analyzing Amazon India product sales data using SQL queries and an interactive Tableau dashboard.

The project covers data cleaning, SQLite database creation, SQL-based analysis, and business insights visualization through a professional Tableau dashboard.

---

## 🎯 Key Business Questions Answered
- Which product category has the highest average rating?
- What is the relationship between discount percentage and rating?
- Which products offer the highest discounts?
- How are products distributed across price ranges?
- Which categories have the most products listed?

---

## 📊 Dashboard Preview
![Amazon Sales Dashboard] <img width="1196" height="880" alt="amazon_sales_dashboard" src="https://github.com/user-attachments/assets/a7589484-5743-4dda-9a21-f4785fc438f5" />

---

## 🔍 SQL Queries Used

| Query | Description |
|---|---|
| Top 10 Highest Rated Products | SELECT + ORDER BY + LIMIT |
| Category wise Analysis | GROUP BY + AVG + COUNT |
| Top Discounted Products | WHERE + ORDER BY |
| Price Range Analysis | CASE WHEN + GROUP BY |
| Discount vs Rating | CASE WHEN + AVG + GROUP BY |

---

## 💡 Key Insights
- **Electronics** dominates with 526 products — largest category
- **OfficeProducts** has highest average rating — 4.31
- Products with **low discounts have higher ratings** (4.17 vs 4.06)
- **Luxury products** are rated higher than budget products
- Maximum discount found — **94%** on USB Type C Adapter
- **Ambrane & boAt** — most discounted Indian brands

---

## 🛠️ Tech Stack

| Category | Technology |
|---|---|
| Language | Python |
| Data Processing | Pandas, NumPy |
| Database | SQLite |
| SQL | 5 analytical queries with GROUP BY, CASE, AVG, COUNT |
| Visualization | Tableau Public |
| Notebook | Jupyter |

---

## 📂 Dataset
- **Source:** Amazon Sales Dataset (Kaggle)
- **Records:** 1,463 products
- **Domain:** E-commerce — Amazon India
- **Features:** Product name, category, price, discount, rating, reviews

---

## 📁 Project Structure
amazon-sales-analysis/

│

├── amazon_sales.ipynb          # Data cleaning + SQL analysis

├── amazon_clean.csv            # Cleaned dataset

├── amazon_sales_dataset.db     # SQLite database

├── dashboard_screenshot.png    # Tableau dashboard

└── README.md                   # Project documentation

---

## 🚀 How to Run

```bash
git clone https://github.com/Ashwini1813/amazon-sales-analysis.git
cd amazon-sales-analysis
pip install pandas numpy
jupyter notebook amazon_sales.ipynb
```

---

## 🎓 Learning Outcomes
- Real-world data cleaning and preprocessing
- SQLite database creation from CSV
- Writing analytical SQL queries (GROUP BY, CASE, AVG, COUNT)
- Business insight generation from data
- Professional dashboard creation in Tableau

---

## 👩‍💻 Developer
**Ashwini Parmar**
