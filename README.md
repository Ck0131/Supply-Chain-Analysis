<div align="center">

<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
<img src="https://img.shields.io/badge/Version-2026.02-blue?style=for-the-badge" />
<img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" />
<img src="https://img.shields.io/badge/License-MIT-orange?style=for-the-badge" />

<br/><br/>

# 📦 Supply Chain Analysis
### End-to-End Power BI Dashboard Report

> *A multi-page Power BI report covering product performance, logistics, inventory, supplier insights, and executive-level KPIs for supply chain operations.*

---

</div>

## 🌟 Overview

This Power BI report provides a **360° view of supply chain performance** — from sales revenue and cost of goods sold to logistics delays, warehouse operations, and supplier contributions. Designed for data-driven decision-making across operations, procurement, and executive teams.

- 📅 **Created From:** Power BI Desktop
- 🗓️ **Report Version:** 2026.02
- 📊 **Pages:** 4 dashboards + 1 drill-through
- 📁 **File Size:** ~1.4 MB

---
## 📊 Dashboard Preview



![Supply Chain Analysis Dashboard](https://github.com/Ck0131/Supply-Chain-Analysis/blob/main/E%20S%20C.png)

## 📋 Report Pages

### 1. 🏠 Overview
> High-level summary landing page with key visuals, branding, and navigation layout.

---

### 2. 🛍️ Product Analysis
> Deep dive into product-level sales performance across categories, regions, and customer types.

| Visual | Description |
|--------|-------------|
| 💳 KPI Cards | Total Revenue, Total COGS, Total Profit, Total Qty |
| 📊 Column Chart | Revenue by Product Category |
| 🗺️ Column Chart | Revenue by Region |
| 🍩 Donut Chart | Dispatch Status Distribution |
| 📈 Line Chart | Revenue Trend over Date Hierarchy (Year → Day) |
| 🔘 Slicer | Filter by Customer Type |

---

### 3. 🚚 Logistics Performance
> Tracks order fulfillment, delivery delays, warehouse city-level performance, and order statuses.

| Visual | Description |
|--------|-------------|
| 💳 KPI Cards | Avg Delay Days, Total Delayed Orders, On-Time Orders, Total Orders |
| 📉 Area Chart | On-Time vs Delayed Orders by Month |
| 🍩 Donut Chart | Orders by Order Status |
| 🍩 Donut Chart | Orders by Delivery Status |
| 📊 Bar Chart | On-Time vs Delayed Orders by Warehouse City |
| 🔘 Slicer | Filter by Product Category |

---

### 4. 🏆 Executive Supply Chain Dashboard
> C-suite summary combining revenue, inventory, delivery performance, supplier shares, and warehouse manager rankings.

| Visual | Description |
|--------|-------------|
| 💳 KPI Cards | Total Revenue, Total Orders, Total Inventory, On-Time Delivery % |
| 📈 Line Chart | Revenue Trend over Time |
| 📊 Clustered Bar | COGS vs Profit by Product Category |
| 🍩 Donut Chart | Revenue Share by Supplier |
| 🎀 Ribbon Chart | Revenue Ranking by Warehouse Manager |
| 📅 Timeline Slicer | Interactive date range filter |

---

## 📐 Data Model

### 🔢 KPI Measures

| Measure | Description |
|---------|-------------|
| `Total Revenue` | Total sales revenue |
| `Total COGS` | Cost of Goods Sold |
| `Total Profit` | Revenue minus COGS |
| `Total Qty` | Total quantity sold |
| `Total order` | Count of all orders |
| `Total Inventory` | Current inventory level |
| `On-Time Orders` | Orders delivered on schedule |
| `Total Delayed Orders` | Orders delivered late |
| `Avg Delay Days` | Average delay duration in days |
| `On Time Delivery %` | Percentage of on-time deliveries |

### 🗂️ Tables

| Table | Key Fields |
|-------|------------|
| `fact_sales_dispatch` | Region, CustomerType, DispatchStatus, DispatchID |
| `fact_orders` | OrderStatus, DeliveryStatus |
| `dim_product` | Category, SubCategory |
| `dim_date` | FullDate (Year, Quarter, Month, Day hierarchy) |
| `dim_supplier` | SupplierName |
| `dim_warehouse` | City, Manager |

---

## 🎨 Custom Visuals Used

| Visual | Version | Description |
|--------|---------|-------------|
| **Timeline Slicer** (BasedOn) | v1.0.1.5 | Interactive date range slicer |
| **Cluster Map** | v1.x | Geographic cluster visualization |

---

## 🛠️ Tech Stack

<div>

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=flat-square&logo=microsoft&logoColor=white)
![Cloud](https://img.shields.io/badge/Power%20BI%20Cloud-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

</div>

---

## 🚀 Getting Started

### ✅ Prerequisites
- Download and install **[Power BI Desktop](https://powerbi.microsoft.com/desktop/)** *(Free)*
### Git Clone 
- ![Git clone](https://github.com/Ck0131/Supply-Chain-Analysis.git)

### 📥 Installation

```bash
# Clone this repository
git clone[https://github.com/Ck0131/Supply-Chain-Analysis.git]

# Navigate into the folder
cd Supply_Chain_PowerBI
```

Then:
1. Open **Power BI Desktop**
2. Click **File → Open report → Browse**
3. Select `Supply_chain_Analysis.pbix`
4. 🎉 Explore all 4 dashboard pages!

---

## 📁 Repository Structure

```
Supply_Chain_PowerBI/
│
├── 📊 Supply_chain_Analysis.pbix    ← Main Power BI Report
└── 📄 README.md                     ← Project documentation
```

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome!

1. 🍴 Fork the repository
2. 🌿 Create a branch: `git checkout -b feature/your-feature`
3. 💾 Commit: `git commit -m "Add your feature"`
4. 📤 Push: `git push origin feature/your-feature`
5. 🔃 Open a Pull Request

---

## 📬 Contact

- 🐛 [Open an Issue](../../issues)
- 💬 [Start a Discussion](../../discussions)

---

<div align="center">

Built with ❤️ using **Microsoft Power BI**

⭐ **Star this repo** if you found it helpful!

</div>
