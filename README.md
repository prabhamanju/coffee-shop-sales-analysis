# BB Coffee Shop — Sales Analysis (2023)
## Objective
Analyze store and product category performance across 3 NYC locations to identify revenue drivers and surface actionable business insights.

## Data Used
Transaction-level sales data from 2023 spread across 4 relational tables — transactions (~149K records), stores, products, and categories — combined using Excel formulas for analysis.

## Key Visuals
-** Store Performance Summary** - total revenue, average revenue, rank and % vs average per store
-** Revenue By Store and Category** - cross-tab breakdown of how each store performs across product categories
-** Category Performanec Summary** - revenue, % of total and ranking for each product category
-** Revenue By Beverage Type* - beverage vs non-beverage revenue split per store

## Insights
- Hell's kitchen generated the heighest revenue among all 3 stores
- Coffee and Tea are the top two revenue generating categories
- Beverage account for 78% of overall sales across all stores
- Astoria shows the strongest beverage preferance of the all 3 locations
- Hell's kitchen leads in food (non beverage) sales

## Tools and Skills Used
**Excel** — VLOOKUP, SUMIF, AVERAGEIF, COUNTIF, RANK, ROUND, Array Formulas, Bar Charts







---

## Workbook Structure

| Sheet | Purpose |
|-------|---------|
| transactions | ~149,000 raw sales records for 2023 |
| stores | 3 NYC store locations with manager info |
| products | Full product catalogue with pricing |
| categories | Product category classification (beverage vs non-beverage) |
| cleaning_formatting_data | All 4 tables joined via VLOOKUP — main analysis table |
| Store Performance Summary | Revenue, ranking and % vs average per store |
| Product Performance Summary | Revenue by product category with ranking |
| Bev Revenue | Beverage vs non-beverage revenue split per store |

---

## Business Questions Answered

1. What is the total revenue per store?
2. Which product category generates the most revenue?
3. Which store manager's store performs best?
4. What percentage of revenue comes from beverages vs non-beverages?

---

## Key Findings

- Hell's Kitchen is the top performing store by total revenue
- Coffee is the #1 revenue-generating category, followed by Tea
- Beverages account for the majority of revenue across all 3 stores
- All 3 stores perform within a close range of the average — consistent performance

---

## Excel Skills Demonstrated

| Skill | Used For |
|-------|---------|
| VLOOKUP | Joining 4 tables, looking up manager, category, seating |
| SUMIF | Total revenue per store and per category |
| AVERAGEIF | Average transaction value per store |
| COUNTIF | Transaction count per store |
| RANK | Ranking stores and categories by revenue |
| ROUND | Formatting percentage outputs |
| Array Formulas | Advanced aggregations across the dataset |
| Charts | Bar charts visualising store and category performance |

---

## Tools Used

- Microsoft Excel

---

## Status

- [x] Data modelling and table joins
- [x] Store performance analysis
- [x] Product category analysis
- [x] Beverage vs non-beverage analysis
- [ ] Dashboard sheet (coming soon)
- [ ] Monthly trend analysis (coming soon)

---

*Project completed as part of my data analytics learning journey.*
