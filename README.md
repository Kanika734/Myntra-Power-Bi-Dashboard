# 🛍️ Myntra Product Analysis Dashboard (Power BI)

This project analyzes product listings from **Myntra** to understand pricing, discounts, brand performance, and customer ratings.  
Raw e-commerce data was cleaned, structured, and visualized to create an interactive Power BI dashboard.

---

## 🔥 Key Business Insights

- Premium brands maintain **high pricing yet high ratings**, indicating strong brand perception.
- Some brands offer **heavy discounts**, but ratings remain low → possible quality issues.
- Low price ≠ good rating — customers prefer **value + quality**.

---

## 🧹 Data Cleaning Performed

| Issue Found | Fix Applied |
|-------------|-------------|
| Missing prices / ratings | Removed invalid rows |
| Duplicate product entries | Removed using `product_link` |
| Discount not available | Created `Discount %` column |
| Rating column was text | Converted rating to numeric format |

> Only the **cleaned dataset** is included here.  
> Raw dataset is not uploaded to avoid size + scraping issues.

---

## 📊 Dashboard Features

- KPI Cards (Total Products, Avg Selling Price, Avg Discount %, Avg Rating)
- Top Brand Analysis (Bar chart)
- Price vs Rating (Line + Column visual)
- Rating Gauge
- Product-level table (price, discount, rating, product link)
- Interactive filters (Brand, Discount Range)

---
## 📂 Repository Contents

| File / Folder | Description |
|---------------|-------------|
| `Myntra_Dashboard.pbit` | Power BI dashboard template |
| `myntra_clean_data.xlsx` | Cleaned dataset used in the dashboard |
| `image/dashboard.png` | Screenshot of the dashboard stored in the `image` folder |
| `README.md` | Documentation |

---
