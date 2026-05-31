# Kenya Product Sales - KPI Dashboard

> An interactive Tableau Public dashboard tracking revenue, profit, units sold, and cost of goods sold across Kenyan counties, products, and customers (2020–2022).

---

##  Live Demo
| Platform | Demonstration |
|---|---|
| Tableau | ![Kenya Sales KPI Dashboard](https://raw.githubusercontent.com/skynet-datagrid-labs/Kenya-Product-Sales/main/assets/SalesKPIKenya.gif) | 
| Description | *Tableau KPI dashboard tracking Revenue, Profit, Units Sold, and Cost of Goods Sold across major beverage companies including Coca-Cola, Dr. Pepper, and Pepsi. Features a quarter range slicer (2020–2023), dynamic metric selector, multi-filter panel by region, company, and category, and cross-filtered views for units sold by month, state, product, and customer.* |

---

## Overview

This project visualises sales performance data for an FMCG business operating across Kenya. It enables stakeholders to monitor key business metrics, drill down by product category, company, and customer, and explore geographic revenue distribution across Kenyan counties.

### Key Metrics Tracked

| Metric | Value (Full Period) |
|---|---|
|  Revenue | 47,712 |
|  Profit | 21,708 |
|  Units Sold | 4,921 |
|  Cost of Goods Sold | 26,004 |

---

##  Features

- **Revenue by Month** — Line chart showing monthly revenue trends from Q1 2020 through Q3 2022
- **Revenue by County** — Choropleth map of Kenya highlighting revenue concentration by region
- **Revenue by Product** — Horizontal bar chart ranking top-selling products (e.g. Stoney Tangawizi, Dormans Coffee, Kericho Gold)
- **Revenue by Customer** — Bar chart ranking top customers by revenue contribution
- **Dynamic Filters** — Slice data by quarter range, company, and product category (Alcoholic, Coffee, Soft Drinks, Tea)
- **Metric Toggle** — Switch the dashboard view between Revenue, Profit, Units Sold, and Cost of Goods Sold

---

##  Repository Structure

```
Kenya-Product-Sales/
│
├── data/               # Raw and processed sales data
│
├── assets/             # Static assets
│   └── SalesKPIKenya.gif   # Dashboard live demo
│
└── README.md
```

---

##  Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Kenya-Product-Sales.git
   ```

2. Open the Tableau workbook (`.twbx`) from the `data/` folder in **Tableau Public Desktop**.

3. Refresh the data source if needed and explore the dashboard.

> **Requirements:** Tableau Public (free) — [Download here](https://public.tableau.com/app/discover)

---

##  Data Scope

- **Period:** Q1 2020 – Q3 2022
- **Geography:** Kenya (county-level)
- **Categories:** Alcoholic beverages, Coffee, Soft Drinks, Tea
- **Companies:** Coca-Cola, Crown Beverages, Kericho Gold (and others)

---

##  Contributing

Contributions, issues, and feature requests are welcome. Feel free to open an issue or submit a pull request.

---

##  License

This project is open source. See the [LICENSE](LICENSE) file for details.

---

*Built  using Tableau Public*
