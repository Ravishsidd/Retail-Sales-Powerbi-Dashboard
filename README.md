# Retail Sales & Business Performance Dashboard

An interactive Power BI project bringing together retail sales, customer support, and marketing performance in one report. The dashboard is built in Power BI Desktop using an Excel workbook as its source.

## Dashboard previews

### 1. Retail Sales Report

![Retail Sales Report](screenshots/retail-sales-report.png)

Explores sales and profitability across month, region, and product category. The page includes sales and cost summaries, sales target achievement, profit achievement, and comparisons by region and category.

### 2. Support UK Report

![Support UK Report](screenshots/support-uk-report.png)

Tracks ticket volumes and resolution performance by agent and support channel. It includes total tickets, resolved tickets, average response time, customer rating, resolution rate, first-response trends, tickets by channel, and minimum/maximum response time.

### 3. Marketing UK Report

![Marketing UK Report](screenshots/marketing-uk-report.png)

Compares Email, Google Ads, and Instagram using website visitors, orders, advertising spend, revenue, cost per order, conversion rate, and return on advertising spend (ROAS).

## Key metrics

| Area | Metrics included |
| --- | --- |
| Retail | Units sold, sales amount, cost amount, profit, sales target achievement, profit achievement |
| Customer support | Total tickets, resolved tickets, average response time, minimum and maximum response time, customer rating, resolution rate |
| Marketing | Website visitors, orders, ad spend, revenue, cost per order, conversion rate, ROAS |

## Files in this repository

```text
.
├── README.md
├── Retail-Sales-Dashboard.pbix
├── Retail-Sales-Source-Data.xlsx
└── screenshots
    ├── retail-sales-report.png
    ├── support-uk-report.png
    └── marketing-uk-report.png
```

- **`Retail-Sales-Dashboard.pbix`** — the Power BI report. Open it with Power BI Desktop to explore the pages, filters, visuals, and measures.
- **`Retail-Sales-Source-Data.xlsx`** — the Excel source workbook. It contains the Retail, Support, and Marketing datasets and their KPI sheets.
- **`screenshots/`** — preview images of the three report pages.

## Tools used

- Microsoft Power BI Desktop
- Microsoft Excel
- DAX (Data Analysis Expressions)

## How to view the project

1. Download or clone this repository.
2. Open `Retail-Sales-Dashboard.pbix` in Power BI Desktop.
3. If Power BI asks for the source workbook location, point it to `Retail-Sales-Source-Data.xlsx` in the downloaded project folder.
4. Refresh the report if required, then use the page tabs and slicers to explore the dashboards.

## Data and privacy note

Review the workbook and report for confidential, commercially sensitive, or personal information before making this repository public. Only publish data that you have permission to share.
