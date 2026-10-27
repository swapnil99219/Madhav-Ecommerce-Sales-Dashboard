# Madhav Ecommerce Sales Dashboard

An interactive Power BI dashboard for analyzing sales, profit, quantity, customer, product-category, payment-mode, and regional performance.

## Tools

- Microsoft Power BI
- Power Query
- DAX
- Data visualization and modeling

## KPIs

- Total Sales
- Total Quantity
- Total Profit
- Average Order Value

## Analysis included

- Profit by month
- Profit by sub-category
- Quantity by category
- Customer-wise sales
- Payment mode distribution
- State-wise performance

## Interactive filters

- Quarter
- State

## Project files

| File | Purpose |
|---|---|
| `Madhav_Ecommerce_Sales_Dashboard.pbix` | Power BI report |
| `Orders.csv` | Order, sales, profit, and product data |
| `Details.csv` | Customer, date, and location details |

## How to use

1. Download the repository.
2. Open the PBIX file in Power BI Desktop.
3. Update the CSV source paths if Power BI requests them.
4. Review relationships and measures before interpreting the visuals.
5. Compare the headline KPI totals with the imported data.

## Validation checklist

- Verify the relationship keys between `Orders.csv` and `Details.csv`.
- Confirm whether Average Order Value is calculated per distinct order.
- Check that monthly trends use a proper date field and chronological sorting.
- Document data source, refresh date, and any known limitations.

## Skills demonstrated

Data cleaning, data transformation, data modeling, DAX, KPI development, interactive dashboard design, and business data analysis.

## Author

Swapnil Rathod
