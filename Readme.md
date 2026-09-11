# A.B Bakery Sales Review Dashboard

![Bakery Dashboard Overview](/0_Resources/Images/bakery_overview.png)

## Introduction

This dashboard analyzes sales performance for A.B Bakery, covering 
revenue and quantity by product, customer type behavior, payment 
method preferences, and weekly sales patterns. It was built in Power 
BI to give the business a quick, visual read on what's selling, who's 
buying, and when.

## Dataset

The dataset tracks individual bakery sales, including:

- **Product** — item sold (Cake, Cookies, Bread)
- **Quantity** — units sold per transaction
- **Revenue / Total** — sales value
- **Payment Method** — Card, Cash, or Transfer
- **Customer Type** — New or Returning
- **week_day** — day of the week the sale occurred

### Dashboard File
The full Power BI file is in [Bakery_project.pbix](Bakery_project.pbix).

## Tools & Skills Used

- **📊 Power BI Desktop** — full report build
- **📈 Visualizations** — combo chart, pie chart, bar chart, clustered 
  column chart, and multi-series line chart

## Dashboard Build

### Sum of Revenue and Quantity by Product
A combo chart comparing revenue and quantity across the three 
products  showing which items drive value versus volume.

### Sum of Revenue by Customer Type
A pie chart splitting revenue between new and returning customers.

### Sum of Quantity by Weekday
A bar chart showing which days of the week generate the most sales 
volume.

### Count of Payment Method
A bar chart showing how customers pay card, cash, or transfer.

### Sum of Quantity by Weekday and Product
A line chart breaking down daily quantity sold, further split by 
product, to spot day-specific product trends.

## Key Insights

- **Cake generates the highest revenue**, despite Cookies having a 
  higher combined revenue-and-quantity presence . Cake is the 
  strongest single revenue driver among the three products.
- **Returning customers drive the large majority of revenue** 
  (76.19%, ~4.46K) compared to new customers (23.81%, ~1.4K)  
  repeat business is the backbone of this bakery's sales.
- **Card is the most-used payment method**, followed closely by Cash, 
  with Transfer used least  worth ensuring card payment 
  infrastructure remains reliable given its dominant share.
- **Friday and Sunday show the highest sales volume**, while 
  Wednesday is the weakest day a pattern likely tied to weekend 
  demand for baked goods.

## Recommendations

- Since returning customers generate over 3x the revenue of new 
  customers, consider loyalty incentives to convert more first-time 
  buyers into repeat customers.
- Leverage the Friday/weekend sales peak with targeted promotions or 
  ensuring adequate stock heading into the busiest days.
- Investigate the low Wednesday volume  a mid-week promotion could 
  help smooth out demand across the week.

## Conclusion

This project demonstrates the ability to turn raw sales data into a 
clear, actionable Power BI dashboard surfacing product performance, 
customer loyalty patterns, and operational timing insights that could 
directly inform inventory and marketing decisions for a small 
business like A.B Bakery.