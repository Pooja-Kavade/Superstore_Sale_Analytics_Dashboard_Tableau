# Sample Superstore – Tableau Dashboard

Interactive Tableau workbook built on the classic **Sample - Superstore** dataset.  
This dashboard provides a comprehensive view of sales performance, profitability, customer behavior, and regional insights.

## Overview

The dashboard analyzes key retail metrics from the Superstore dataset and enables users to explore:

- Overall Sales, Profit, Discount & Quantity
- Performance by Category, Sub-Category & Product
- Customer and Segment analysis
- Regional and State-level insights
- Shipping mode and order trends
- Returns analysis

## Key Features

- **KPI Cards**: Total Sales, Total Profit, Total Discount, Total Quantity
- **Interactive Filters**: Region, Category, Sub-Category, Segment, Ship Mode, Date
- **Parameters**:
  - Top Customers (adjustable from 5 to 20)
  - Profit Bin Size (for profit distribution analysis)
- Multiple visualizations: Bar charts, Line charts, Maps, Scatter plots, Heatmaps, Tables
- Dynamic sorting and highlighting

## Data Sources

The workbook uses the standard **Sample - Superstore** Excel file containing three sheets:

| Sheet     | Description                          |
|-----------|--------------------------------------|
| Orders    | Transaction-level sales data         |
| People    | Regional Manager mapping             |
| Returns   | Returned orders information          |

## How to Use

1. Download the `.twb` file (or `.twbx` if packaged with data).
2. Open it in **Tableau Desktop** or **Tableau Public**.
3. If the data connection is broken, reconnect it to the Sample - Superstore Excel file.
4. Use the filters and parameters to explore the data interactively.

## Tools Used

- Tableau Desktop / Tableau Public
- Sample Superstore dataset (Excel)

## Project Structure

```
├── sample_superstore_dashboard.twb   # Tableau workbook
├── README.md                         # Project documentation
└── (optional) Sample - Superstore.xls
```

## Author

Created as a Tableau visualization project using the standard Superstore dataset.

---

Feel free to fork, modify, or use this dashboard as a starting point for your own analysis!
```
