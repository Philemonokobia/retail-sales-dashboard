# Retail Sales Performance Dashboard

An interactive Excel dashboard analyzing ₦456,000 in retail sales across product category, customer age, and gender — built with slicers so any of those cuts can be explored instantly, without touching a single formula.

![Dashboard screenshot](dashboard-screenshot.png)

## Business problem

Working from a raw sales transactions dataset, the goal was to answer a set of recurring business questions in one self-serve view:
- What's our total sales, units sold, and average order value?
- Which product category drives the most revenue?
- Who are our customers — how do sales break down by age and gender?
- How do sales trend month to month?

## Approach

**Data modeling**
Built calculated fields directly from the transactions table:
- **Total Sales** = SUM(Total Amount)
- **Units Sold** = SUM(Quantity)
- **Average Order Value (AOV)** = Total Sales ÷ Number of Transactions

**Dashboard structure**
- KPI cards across the top: Total Sales, Units Sold, Average Order Value
- Bar chart: Sales by Product Category
- Donut chart: Customers by Gender
- Line chart: Monthly Sales Trends
- Bar chart: Customers by Age Group
- Slicers for Gender, Product Category, Age Group, and Month, so every chart on the dashboard filters together

## Key insights

- **Total sales reached ₦456,000** across 2,514 units sold, for an average order value of ₦456.
- **Electronics is the top-performing category** (~₦157K), narrowly ahead of Clothing (~₦155K), with Beauty trailing (~₦145K).
- **The customer base is nearly evenly split by gender** — 510 female vs. 490 male — suggesting marketing doesn't need heavy gender-specific targeting.
- **Sales are strongly seasonal**: they peaked in May (~₦57K) and fell to their lowest point in September (~₦28K) — a drop of nearly 50% from the year's high point.
- **The 48–57 age group is the largest customer segment**, with 58–67 the smallest — useful for age-targeted promotions.

## Tools used

Microsoft Excel · PivotTables · PivotCharts · Slicers

## What I'd do with more time

- Dig into *why* September dipped so sharply — promotion timing, stock issues, or a seasonal pattern worth planning around.
- Cross-reference product category performance against gender and age segments to see if certain categories skew toward specific customer groups.
- Add a rolling 3-month average line to the monthly trend chart to separate real trend shifts from month-to-month noise.

---
*Note: dataset used is a training assignment dataset, not real company sales data.*
