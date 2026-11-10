# 👟 Adidas USA Sales Dashboard

An interactive **Excel dashboard** analyzing Adidas sales performance across the United States from **2020 to 2021** — by retailer, product category, region, state, sales channel, and month.

## 📌 Overview

This project turns raw Adidas transaction data into a clear, filterable business dashboard. It helps answer questions such as:

- Which retailers and regions drive the most revenue and profit?
- Which product categories sell best?
- How do sales change month to month?
- Which sales channel (In-store, Outlet, Online) performs best?
- Which states contribute the most to total sales?

## 📊 Key Metrics

| Metric | Value |
|---|---|
| Total Sales | **$899.9M** |
| Operating Profit | **$332.1M** |
| Units Sold | **2,478,861** |
| Average Operating Margin | **~42%** |
| Transactions | **9,648** |
| Period | Jan 2020 – Dec 2021 |

## 🔍 Highlights

- **Top retailer:** West Gear (~$243M), followed by Foot Locker (~$220M) and Sports Direct (~$182M)
- **Top region:** West (~$270M); Midwest is the lowest (~$136M)
- **Top product:** Men's Street Footwear (~$209M), followed by Women's Apparel (~$179M)
- **Top channel:** In-store (~$357M), then Outlet (~$296M) and Online (~$248M)
- **Growth:** 2021 sales (~$718M) were roughly 4× 2020 sales (~$182M)

## 🖼️ Dashboard Components

| Visual | Description |
|---|---|
| KPI cards | Units sold, total sales, average sales, operating profit |
| Doughnut chart | Total sales by product category |
| Bar chart | Total products sold by retailer |
| Line chart | Total sales by month |
| Map chart | Total sales by state |
| Slicers | Interactive filters for **Retailer**, **Product**, and **Month** |

## 🗂️ Workbook Structure

| Sheet | Purpose |
|---|---|
| `Data Sales Adidas` | Raw dataset (Excel Table, 9,648 rows × 13 columns) |
| `Pivot Analysis` | PivotTables feeding every KPI and chart |
| `Dashboard` | Final interactive dashboard with charts and slicers |

### Data Dictionary

| Column | Description |
|---|---|
| Retailer | Retail partner (6 retailers) |
| Retailer ID | Unique retailer identifier |
| Invoice Date | Date of the sale |
| Region | US region (West, Northeast, Southeast, South, Midwest) |
| State / City | Location of the sale (50 states, 52 cities) |
| Product | Product category (6 categories) |
| Price per Unit | Selling price per unit |
| Units Sold | Number of units sold |
| Total Sales | Revenue (Price × Units) |
| Operating Profit | Profit from the sale |
| Operating Margin | Operating Profit ÷ Total Sales |
| Sales Method | In-store, Outlet, or Online |

## 🛠️ Tools & Techniques

- Microsoft Excel
- Excel Tables and PivotTables
- Slicers for interactive filtering
- PivotCharts (doughnut, bar, line) and a map chart
- Data cleaning and KPI design

## 🚀 How to Use

1. Download or clone this repository.
2. Open `Adidas_USA.xlsx` in **Microsoft Excel** (2016 or later recommended; the map chart requires a recent version).
3. Go to the **Dashboard** sheet.
4. Use the slicers to filter by retailer, product, and month — all visuals update automatically.

> ⚠️ Slicers and the map chart are not fully supported in Google Sheets or LibreOffice. Use desktop Excel for the best experience.

## 📁 Repository Structure

```
adidas-usa-sales-dashboard/
├── Adidas_USA.xlsx
├── README.md
└── Imgs/
    └── Adidas_Logo.png
    └── improvement.png
    └── sales.png
    └── sold-tag-icon.png
    └── tag.png
```

## 👤 Author

**Mahmoud**
Data analysis
