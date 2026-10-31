# Sales Analysis Dashboard (2014–2018)

An Excel-based sales analysis project that explores sales performance, profitability, order volume, product categories, and geographic results from 2014 through 2018. The workbook includes a dashboard, KPI summaries, charts, and reference data for customers, products, and delivery regions.

## Project objectives

- Track sales and profit trends over time.
- Compare annual performance and year-over-year changes.
- Review order volume, units sold, and profit margin.
- Identify leading product categories and states.
- Present the results in an interactive Excel dashboard.

## Key findings

The annual KPI summary reports the following results for 2014–2018:

| KPI | Result |
|---|---:|
| Total sales | $79.16M |
| Total profit | $30.22M |
| Total units ordered | 34,900 |
| Total orders | 4,132 |
| Weighted profit margin | 38.2% |
| Highest sales year | 2015 — $16.83M |
| Highest profit year | 2017 — $6.42M |
| Leading state in the state summary | California — $9.26M |
| Leading category in the Top 5 summary | Category 7 — $1.89M |

### Annual performance

| Year | Sales | Profit | Units | Orders | Sales YoY |
|---|---:|---:|---:|---:|---:|
| 2014 | $15.90M | $6.16M | 7,155 | 856 | — |
| 2015 | $16.83M | $6.31M | 7,268 | 855 | +5.9% |
| 2016 | $15.65M | $5.87M | 6,949 | 823 | -7.0% |
| 2017 | $16.49M | $6.42M | 7,230 | 849 | +5.4% |
| 2018 | $14.30M | $5.46M | 6,298 | 749 | -13.3% |

2015 produced the highest sales, while 2017 had the highest profit and the strongest annual profit margin (about 38.9%). 2018 was the weakest year in the annual summary, with sales down 13.3% and profit down 15.0% versus 2017.

## KPIs

- **Total Sales:** Sum of sales value.
- **Total Profit:** Sum of profit value.
- **Profit Margin:** Total profit divided by total sales. The overall figure above is weighted across all years.
- **Order Count:** Count of order numbers.
- **Units Ordered:** Sum of order quantity.
- **Average Order Value (AOV):** Total sales divided by order count. This can be added as a dashboard measure.
- **Year-over-Year Sales Growth:** Current year sales divided by previous year sales, minus one.

## Workbook contents

| Worksheet | Purpose |
|---|---|
| Dashboard | Overview of sales KPIs and charts |
| KPI | Monthly sales, profit, order quantity, order count, and margin summaries |
| KPI YOY | Annual sales and profit results with year-over-year comparisons |
| Combo Chart | Monthly sales and profit chart data |
| Waterfall Chart | Profit by product category |
| Pie Chart | Sales mix by product category |
| Map Chart | Sales by state |
| Top 5 Cat | Top five product categories by sales |
| Sales Orders | Order-level sales records |
| Customers | Customer lookup table |
| Regions | Delivery location reference data |
| State Regions | State-to-region mapping |
| Products | Product and category lookup table |
| Multi Scenario | Scenario-analysis template |

## Data and tools

- **Source:** `Excel Project with Dashboard.xlsx`
- **Format:** Microsoft Excel workbook (`.xlsx`)
- **Tools:** Excel charts, KPI summaries, and dashboard views
- **Data coverage:** 2014–2018; the Sales Orders worksheet contains 42,737 data rows (excluding the header).

## How to use

1. Download or clone this repository.
2. Open the Excel workbook in Microsoft Excel.
3. Start with the **Dashboard** sheet for the summary view.
4. Use the KPI and chart sheets to explore annual, monthly, category, and state performance.
5. Use the reference worksheets to interpret customer, product, and region fields.

## Notes

- Monetary values are shown in USD based on the workbook’s currency field and KPI summaries.
- Category labels appear as generic names (for example, “Category 7”) in the workbook.
- The monthly totals shown on **Combo Chart** do not appear to match the monthly totals on **KPI**. Confirm that both summaries use the same date range and filters before combining them in a presentation.
- Results in this README are based on the workbook’s existing summaries; refresh the workbook’s PivotTables and charts if the underlying data changes.

## Repository structure

```text
.
├── README.md
└── Excel Project with Dashboard.xlsx
```

## Author

**Mehjabeen Shaikh**

