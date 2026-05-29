# bike_sales_store
# 🚲 Bike Store Analytics Project
Welcome to the Bike Store Analytics Project repository! 🚀
This project explores transactional bike sales data to uncover actionable business insights — covering sales trends, product performance, customer behavior, and revenue patterns. Designed as a portfolio project, it highlights practical skills in data analytics and SQL-based reporting.

---

## 📖 Project Overview
This project analyzes a bike store dataset spanning **2016 – 2019**, containing **9 tables** with the following structure:

| Table | Rows | Description |
|---|---|---|
| `brands` | 9 | Bicycle manufacturers |
| `categories` | 7 | Product categories |
| `products` | 321 | Product catalogue with pricing |
| `customers` | 1,445 | Customer contact and address details |
| `stores` | 3 | Retail store locations |
| `staffs` | 10 | Store staff and management hierarchy |
| `orders` | 1,615 | Order headers placed by customers |
| `order_items` | 4,722 | Line items per order |
| `stocks` | — | Per-store product stock levels |

### Dataset Codes & Abbreviations

**`orders.order_status`**

| Code | Meaning |
|---|---|
| 1 | Pending — order received, not yet processed |
| 2 | Processing — order confirmed and being prepared |
| 3 | Rejected — order was cancelled or rejected |
| 4 | Completed — order shipped and fulfilled |

**`customers.state` / `stores.state`**

| Code | Meaning |
|---|---|
| NY | New York |
| CA | California |
| TX | Texas |

**`staffs.active`**

| Code | Meaning |
|---|---|
| 1 | Active — staff member currently employed |
| 0 | Inactive — staff member no longer employed |

**`order_items.discount`** — Stored as a decimal fraction. e.g. `0.05` = 5% off, `0.20` = 20% off.
Effective line total = `quantity × list_price × (1 − discount)`

---

## 📊 Analytics & Insights
The analysis delivers insights across the following areas:

- **Sales Trends** — Monthly and yearly revenue performance
- **Store Performance** — Revenue breakdown by store location
- **Product Performance** — Top 10 best selling products by revenue
- **Order Analysis** — Order status breakdown across all locations
- **Customer Behavior** — Top 10 customers by total spend
- **Revenue Analysis** — Total revenue lost to discounts

---

## 🎯 Skills Demonstrated

- SQL Development
- Data Cleaning
- Business Intelligence & Reporting

---

## 🛠️ Tech Stack

- SQL Server
- SQL
- Power BI

---

## 📂 Repository Structure

```bash
bike_sales_store/
│
├── datasets/              # Raw source CSV files
├── docs/                  # Power BI charts and graphs
├── scripts/               # SQL analytics questions scripts
│
├── README.md
└── LICENSE
```

---

## ⚙️ Setup & Installation

### Clone Repository
```bash
git clone https://github.com/manhazyare/Bike-store-analysis.git
```

### Navigate to Project
```bash
cd bike_sales_store
```

---

## 🛡️ License
This project is licensed under the **MIT License**.
You are free to use, modify, and distribute this project with proper attribution.

---

## 🌟 About Me
Hi there! I am passionate about Data Analytics and turning raw data into meaningful business insights. This repository is part of my portfolio showcasing practical experience in data analysis and reporting.

---

## 🔗 GitHub Repository
https://github.com/manhazyare/Bike-store-analysis
