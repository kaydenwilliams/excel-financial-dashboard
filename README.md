# Excel Financial Dashboard | Microsoft Financial Sample

## Overview
Interactive Excel financial dashboard analyzing **$118.7M in total revenue** across 5 countries, 6 products, and 5 customer segments. Built using Pivot Tables, PivotCharts, dynamic slicers, and KPI summary cards to surface revenue drivers, profitability gaps, and discount inefficiencies.

## Tools:
- Microsoft Excel
- Pivot Tables & PivotCharts
- KPI Cards
- Dynamic Slicers

## Dataset: 
Microsoft Financial Sample
https://learn.microsoft.com/en-us/power-bi/create-reports/sample-financial-download

## Business Questions
1. Which products are generating the most revenue?
2. How does revenue trend over time — are there seasonal patterns?
3. Which countries are performing strongest and weakest?
4. How much are dscounts costing the business and where are they concentrated?
5. Which customer segments are most and least profitable?

## KPIs
- Are we making money? → **Profit Margin %** → Profit / Sales (you calculate this)
- How much money came in? → **Total Revenue** → Sales column
- How much did we actually keep? → **Total Profit** → Profit column
- How much did discounts cost us? → **Total Discount Amount** → Discounts column
- How many units moved? → **Total Units Sold** → Units Sold column

## Key Findings
- **Paseo generated $32.4M in sales** — the top-performing product, nearly double the next closest product
- **Revenue peaks in October and November**, indicating a consistent seasonal demand pattern across all years
- **Mexico underperforms all other countries** despite operating in the same product catalog
- **High discount band accounts for $5.5M of $9.2M in total discounts** — directly compressing the 14.23% overall profit margin
- **Government segment generated $11.4M in profit** while the Enterprise segment operated at a loss

## Files
```
excel-financial-dashboard/
├── excel-financial-dashboard.xlsx   # Full interactive dashboard
├── executive_summary.pdf            # One-page findings and recommendations
└── README.md
```

## Dashboard Features

| Feature | Details |
|---|---|
| KPI Cards | Total Revenue, Profit Margin %, Total Profit, Total Discount Amount, Total Units Sold |
| Charts | Sales by Product, Revenue over Time, Sales by Country, Discount Amount by Discount Band, Profit by Segment |
| Slicers | Country, Segment — filter all visuals simultaneously |

## Business Recommendations
- Prioritize Paseo in inventory and marketing planning; apply its performance drivers to underperforming products such as Carretera and Montana
- Increase inventory and marketing spend in Q3 to prepare for the October–November seasonal demand surge and avoid stockouts
- Audit Mexico's pricing, distribution, and marketing strategy and increase targeted regional investment to close the performance gap
- Cap High-band discounts and shift promotions toward Medium-band discounts to protect the 14.23% profit margin
- Expand Government segment contracts and conduct an immediate Enterprise pricing and cost structure audit
