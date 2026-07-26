# Banking Analytics Dashboard

An interactive Power BI report for exploring customer demographics, financial health, transactions, card activity, and behavioral patterns.

**[View the live Power BI report](https://app.powerbi.com/view?r=eyJrIjoiNDViZTEwYWYtZDRjZS00YjQyLTk4NWUtMmUzYjExNzhlNDIwIiwidCI6IjA1MjEzYjk4LTdiNzAtNDNlOS05YjVmLWVkYmMzODhmNjRkMCJ9)**

## Business objective

The dashboard turns banking data into an accessible analytical experience that supports:

- Customer segmentation by demographic and income attributes
- Financial-health analysis using debt, risk, and debt-to-income measures
- Transaction analysis by time, geography, and payment behavior
- Card and account activity exploration
- Cross-filtered investigation across multiple report pages

## Report structure

The report is organized around four analytical areas:

1. **Demographics** — Customer composition and segment comparison
2. **Financial health** — Debt, risk, balances, and debt-to-income analysis
3. **Transactions** — Volume, value, payment methods, location, and time trends
4. **Card details** — Card-level behavior and activity

## Data model

The model connects customer, account, card, and transaction information so that selections flow consistently across report pages. Power Query handles preparation and standardization, while DAX provides reusable measures and KPI logic.

## DAX and analytical measures

Measures are grouped by business purpose:

- Customer and transaction counts
- Total and average transaction values
- Balance and accumulated-debt measures
- Risk and debt-to-income indicators
- Time-based comparisons and segment-level KPIs

## Technology

- Power BI
- DAX
- Power Query
- SQL
- Data modeling
- Custom visuals

## Screenshots

### Project overview

![Project overview](screenshots/portada.png)

### Dashboard preview

![Dashboard preview](screenshots/mockup.png)

### Demographics

![Demographics analysis](screenshots/Demographics.png)

### Financial health

![Financial health analysis](screenshots/Financial%20Health.png)

### Transactions

![Transaction analysis](screenshots/Transactions.png)
