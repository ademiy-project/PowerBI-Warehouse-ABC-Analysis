# Power BI: Warehouse Sales Report & ABC Analysis

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logoColor=black) ![DAX](https://img.shields.io/badge/DAX-0E4C92?style=for-the-badge&logoColor=white)

An interactive Power BI report for analyzing warehouse sales and classifying products with **ABC analysis**. The report has an app-like layout: a home page with section tiles, a side navigation menu, KPI cards, bookmark switches and a dark theme.

## Report Pages
| # | Page | What it shows |
|---|---|---|
| 1 | **Главная (Home)** | Clickable section tiles that open the report pages |
| 2 | **Отчёт по складам (Warehouse Report)** | KPI cards, sales and deals by warehouse (table and bar chart), sales dynamics of the top-3 warehouses, with a **Rating / Dynamics** bookmark switch |
| 3 | **ABC-анализ (ABC Analysis)** | ABC category for every product, share of each category, donut chart of the category structure |

## Data
Sales records with the following fields:
| Column | Description |
|---|---|
| `Дата` | Sale date |
| `Склад` | Warehouse |
| `Контрагент` | Customer |
| `Номенклатура` | Product |
| `Количество` | Quantity sold |

The `ABC` table assigns each product a category (A / B / C) based on its share of total sales.

## KPIs
- **Количество продаж:** total quantity sold
- **Количество товаров:** number of unique products
- **Количество клиентов:** number of unique customers
- **Уникальные дни продаж:** number of unique sales days

## ABC Analysis
Products are ranked by sales quantity and split by their cumulative share of total sales (Pareto principle):
- **A:** the few products that bring most of the sales and need the most attention
- **B:** products with a medium contribution
- **C:** the many products with a small contribution, candidates for assortment optimization

## Design & UX
- **Home page** with clickable tiles for each section
- **Side navigation menu** (Главная / Отчёт по складам / ABC-анализ) on every page, with the current page highlighted in blue
- **Grid layout:** visuals aligned to a grid, filters moved to the header, 4 KPI cards in one row
- **Bookmark switch** "Рейтинг / Динамика" in a single row to toggle between views
- **Donut chart** instead of a pie chart
- **Dark theme** with A/B/C colors and table formatting adjusted for readability on a dark background
- **Slicers** for date, warehouse, customer and product

## Tools
Power BI Desktop, Power Query, DAX

## Files
- `Warehouse_Report_redesign.pbix`: Power BI report

## How to View
Open `Warehouse_Report_redesign.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free). Use **Ctrl + click** on buttons to navigate in edit mode.

## Topics Covered
**Power BI**
- Page navigation with buttons, bookmarks
- Report design: grid layout, custom theme, dark UI, background images
- KPI cards, tables, bar, line and donut charts
- Slicers and cross-filtering
- Conditional formatting

**Analytics**
- ABC analysis (Pareto principle)
- Warehouse performance ranking
- Sales dynamics and trend analysis
- Inventory and assortment analysis

## Keywords
`power-bi` `powerbi` `dax` `power-query` `abc-analysis` `pareto` `warehouse-analytics` `inventory-analysis` `sales-analysis` `dashboard` `data-visualization` `report-design` `ui-design` `bookmarks` `navigation` `kpi` `business-intelligence` `data-analyst` `portfolio-project`
