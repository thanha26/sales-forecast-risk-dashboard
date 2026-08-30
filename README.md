# Sales Forecast Accuracy & Demand Risk Analytics Dashboard

A 2-page Power BI dashboard analyzing retail sales performance, forecast accuracy, and inventory risk across categories, regions, and time.

## Problem Statement

Retail businesses need to understand not just what they're selling, but how accurately they're forecasting demand — and where inventory risk (stockouts and overstocking) is concentrated. This dashboard answers:
- How accurate are our sales forecasts, and where do they break down?
- Which categories and regions drive the most revenue?
- Where is inventory risk highest, and how has it changed over time?
- Do promotions measurably impact sales?

## Tools Used
- **Power BI Desktop** — report building, data modeling
- **DAX** — custom measures (Forecast Accuracy %, WAPE %, Stockout/Overstock Risk, Avg Inventory Gap)
- **Power Query** — data cleaning and transformation
- **SQL** — initial data exploration and analysis

## Dashboard Pages

### Page 1: Sales Forecast Accuracy & Demand Analytics
Executive overview covering net revenue, units sold, forecast accuracy, and WAPE, with breakdowns by category, region, and promotion impact.

![Page 1](page1-sales-overview.png)

### Page 2: Inventory & Demand Risk Analytics
Deep dive into stockout and overstock risk by category and region, inventory gap trends over time, and a category x region risk matrix.

![Page 2](page2-risk-analytics.png)

## Key Features
- Custom DAX measures for forecast accuracy and inventory risk scoring
- Interactive slicers (Year, Category, Region) synced across visuals
- Custom tooltip page showing category-level revenue trends on hover
- Page navigation buttons for seamless user experience
- Professional color theme applied consistently across both pages

## Key Insights
- Forecast accuracy sits at 93.92% overall, with a WAPE of 6.08%, indicating strong forecast reliability with some room for improvement in specific categories.
- [Add your own insight here — e.g., "Clothing carries the highest stockout risk, while Electronics shows the highest overstock risk, suggesting a need for category-specific inventory strategies."]
- [Add another insight — e.g., "Revenue is fairly evenly distributed across regions, with East slightly outperforming."]

## Files in This Repo
- `sales-forecast-risk-dashboard.pbix` — full interactive Power BI file
- `dashboard-export.pdf` — static PDF export of both pages
- `page1-sales-overview.png`, `page2-risk-analytics.png` — page screenshots
