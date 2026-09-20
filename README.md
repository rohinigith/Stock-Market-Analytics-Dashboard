# Stock Market Analytics Power BI Dashboard

An interactive **Microsoft Power BI dashboard** for exploring company information and stock-market activity through visual analytics.

## Dashboard Overview

The report contains two Power BI pages with analysis covering:

### Page 1 — Company & Market Overview
- Company selector
- Company name
- Sector
- Country
- Geographic company distribution
- Trading volume
- Turnover
- Report date

### Page 2 — Company & Stock Details
- Company distribution by country
- Company ID and name
- Sector
- Stock-price date hierarchy
- Stock-price high values
- Shares traded

## Data Model

The report uses the following core entities identified in the PBIX:

- **Companies** — company name, sector, country, company ID and date information
- **StockPrices** — stock-price dates, volume and price-related fields
- **StockTransactions** — turnover and shares-traded information

## Visualizations

The report includes Power BI visuals such as:

- Slicer
- Cards
- Filled map
- Gauges
- Treemap
- Table

## Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX / Power BI data modeling
- Data Visualization
- Business Intelligence

## How to Use

1. Download `Stock-Market-Analytics-Dashboard.pbix`.
2. Install **Microsoft Power BI Desktop**.
3. Open the `.pbix` file.
4. If prompted, configure the required data-source credentials or paths.
5. Refresh the report if necessary.

> GitHub can store the `.pbix` file, but it cannot render the interactive Power BI report directly in the repository. The PBIX file must be opened with Power BI Desktop.

## Repository Structure

```text
stock-market-powerbi/
├── Stock-Market-Analytics-Dashboard.pbix
├── README.md
├── LICENSE
├── .gitignore
└── docs/
    ├── dashboard-overview.md
    └── assets/
        ├── report-background-1.jpg
        └── report-background-2.jpg
```

## License

MIT License
