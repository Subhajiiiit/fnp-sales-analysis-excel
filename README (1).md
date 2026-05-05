# 🌸 FNP Sales Analysis Dashboard — Excel Project

![Dashboard Preview](dashboard.png)

---

## 📌 Project Objective

This project analyzes the sales performance of **Ferns N Petals (FNP)** — a gifting and flowers brand — using Microsoft Excel.
The goal is to uncover revenue trends, top-performing products, customer ordering patterns, and city-wise demand to support data-driven business decisions.

The final output is an **interactive Excel dashboard** with slicers, pivot charts, and KPI cards that allow stakeholders to filter and explore data dynamically.

---

## ❓ Questions / KPIs Addressed

| # | Business Question |
|---|-------------------|
| 1 | What is the **total number of orders** placed? |
| 2 | What is the **total revenue** generated? |
| 3 | What is the **average order-to-delivery time** (in days)? |
| 4 | What is the **average customer spending** per order? |
| 5 | Which **occasions** (Anniversary, Birthday, Diwali, etc.) drive the most revenue? |
| 6 | How does **revenue trend across months** — are there seasonal peaks? |
| 7 | Which **product categories** (Cakes, Colors, Mugs, Sweets, etc.) perform best? |
| 8 | Which **top 10 cities** place the highest number of orders? |
| 9 | At which **hours of the day** are orders most frequently placed? |
| 10 | What are the **Top 5 products by revenue**? |

---

## ⚙️ Process

### 1. 🗂️ Data Collection
- Raw transactional sales data was collected containing fields such as Order ID, Product Name, Category, Occasion, City, Order Date, Delivery Date, Quantity, and Revenue.

### 2. 🧹 Data Cleaning
- Removed **duplicate records** and blank rows to ensure data integrity.
- Standardized **date formats** across Order Date and Delivery Date columns.
- Created a calculated column: **Order-to-Delivery Days** = `Delivery Date − Order Date`.
- Extracted **Order Hour** from the timestamp to enable time-of-day analysis.
- Validated and corrected **city name inconsistencies** using Find & Replace.
- Ensured all **revenue and quantity** values were numeric and free of errors.

### 3. 📊 Pivot Tables Created

| Pivot Table | Purpose |
|-------------|---------|
| Revenue by Occasion | Measures revenue contribution per gifting occasion |
| Revenue by Month | Tracks monthly revenue trend across the year |
| Revenue by Category | Compares product categories by total revenue |
| Top 10 Cities by Order Count | Identifies highest-demand geographic locations |
| Revenue by Order Hour | Analyzes customer buying behavior by time of day |
| Top 5 Products by Revenue | Highlights the best-selling individual products |

### 4. 📈 Dashboard Design
- All pivot charts were assembled on a **single dashboard sheet**.
- **KPI Cards** were added at the top displaying: Total Orders, Sum of Revenue, Avg. Order-to-Delivery Time, and Average Spending.
- **Slicers** were connected across charts for:
  - 📅 Order Date (by Month)
  - 📦 Delivery Date (by Month)
  - 🎉 Occasion
- A consistent **green & white color theme** was applied for visual clarity and brand alignment.

---

## 📊 Dashboard

![FNP Sales Analysis Dashboard](dashboard.png)

> **Key Highlights from the Dashboard:**
> - 📦 **1,000** total orders recorded
> - 💰 Total revenue of **₹35,20,984**
> - 🚚 Average order-to-delivery time: **5.53 days**
> - 💳 Average customer spending: **₹3,520.98**
> - 🎂 **Raksha Bandhan** and **Anniversary** are the top revenue-generating occasions
> - 📅 Revenue peaks observed in **February** and **August**
> - 🏙️ **Srikakulam** leads among top cities by order volume
> - ⏰ Orders spike during **late night and early morning hours**
> - 🏆 **Deserunt Box** is the highest-revenue product

---

## 🛠️ Tools Used

- **Microsoft Excel** — Pivot Tables, Pivot Charts, Slicers, Conditional Formatting, Dashboard Design

---

## 📁 Files in this Repository

| File | Description |
|------|-------------|
| `FNP_Sales_Dashboard.xlsx` | Main Excel file with raw data, pivot tables, and dashboard |
| `dashboard.png` | Screenshot of the final dashboard |
| `README.md` | Project documentation |

---

## 🙋 About

**Author:** Subhajit  
**Domain:** Sales Analytics / Business Analysis  
**Tools:** Microsoft Excel  

> 💡 *This project is part of my journey transitioning into Business Analysis — building hands-on skills in data cleaning, pivot analysis, and dashboard reporting.*

---

⭐ *If you found this project helpful, feel free to star the repository!*
