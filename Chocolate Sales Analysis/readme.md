# Chocolate Sales Dashboard – Project Summary

**Overview:**
This project is a fully interactive Excel-based sales dashboard developed to analyze the performance of a chocolate sales business. It brings together various datasets like sales, location, product, and team information to present a clean, user-friendly interface for insights and decision-making.
The dashboard is built using Power Pivot, a structured data model, and several advanced Excel features to provide real-time, dynamic analysis.

The goal was to turn raw data into an interactive visual dashboard that:
- Summarizes business performance
- Tracks key performance indicators (KPIs)
- Highlights team and individual contributions
- Offers trend and profit analysis
- Supports dynamic filtering and sorting

**Tools & Techniques Used**
- Excel Power Pivot & Data Model
- Pivot Tables & Slicers
- Conditional Formatting & Icon Sets
- Dynamic Named Ranges
- INDEX, MATCH, XMATCH formulas
- Data Visualization (charts, sparklines, image mapping)
- Custom Formatting for KPIs

**Key Elements:**
- KPIs such as Total Sales, Cost, Profit, Shipments, Boxes, and Profit %
- MoM (Month-over-Month) performance changes
- Dynamic slicers to filter by product category
- Country-wise visuals, including map highlights and flags
- Team-wise performance trends
- Conditional formatting to highlight growth and decline
- Sparkline charts for product trend analysis

**1. Data Structuring**
I started by importing and organizing the core datasets—sales, product details, location info, and team data—into a single data model using Power Pivot. I also ensured all data was formatted appropriately (currency, percentages, etc.).
**2. Creating Calculated Measures**
Using custom formulas, I calculated values like Total Cost, Shipments, Profit, and Profit Percentage. These were formatted to improve readability.
**3. Date-wise Analysis**
I created a year-month hierarchy to observe trends over time. By tweaking the pivot table layout (turning off subtotals and grand totals), I made the view cleaner and easier to interpret.
**4. Slicer Integration**
A slicer was added to filter the dashboard based on product categories—chocolate bars, bites, and others. I also added logic to display whether one, multiple, or all categories were selected.
**5. MoM KPI Calculations**
I computed current and previous month values for key metrics, then derived the Month-over-Month percentage change. These KPIs were displayed in tile format with neat currency formatting.
**6. Visual Indicators**
I applied icon-based conditional formatting to show whether values increased or decreased month-over-month.
**7. Country Visuals**
I used INDEX, XMATCH, and named ranges to dynamically display country-related images on the dashboard, based on performance metrics like sales and profit percentage.
**8. Sorting Logic**
Sorting functionality was added to the dashboard—users can sort country or team data by either total sales or profit percentage. This was done using helper columns and formulas.
**9. Team Performance Analysis**
I built a report to compare individual and team-level performance, including sorted trends and visual indicators.
**10. Product Trend Analysis**
Finally, sparklines and conditional formatting were used to show how different product categories have performed over time, with sorting enabled for better clarity.
