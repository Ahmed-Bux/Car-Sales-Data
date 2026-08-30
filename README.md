# 🚗 Car Sales Dashboard
## Project Overview 📌
 * This project involves the development of an enterprise-grade **Car Sales Dashboard** built using **Power BI**. The dashboard tracks key performance indicators (KPIs) over Year-to-Date (YTD) and Month-to-Date (MTD) timelines to provide actionable operational insights into regional distribution, product metadata, and dealer network efficiency.
 * The business goal was to build a centralized intelligence tool that allows sales managers and automotive executives to track real-time sales revenue ($371.2M total), inspect granular transaction logs, optimize pricing strategies, and evaluate inventory rotation speeds.
## Project Objectives 🎯
 * Design a high-impact, dark-themed 2-page interface optimized for retail executive reporting.
 * Implement time-intelligence indicators to compare YTD and MTD metrics against historical variance.
 * Break down transaction characteristics across car metadata including Body Style, Color, Transmission, and Engine types.
 * Evaluate granular transaction histories through deep tabular logging layouts.
 * Track dealership location efficiency and geographic sales patterns to optimize regional logistics.
## Tools & Technologies 🛠️
### Data Visualization & Modeling
 * **Power BI Desktop** (Canvas layout & UI/UX implementation)
 * **DAX (Data Analysis Expressions)** (Calculated columns for time intelligence: YTD/MTD growth metrics)
 * **Power Query** (M Language for data normalization, data type assignment, and cleaning pipelines)
## Power BI Dashboard 📊
### The dashboard features 2 highly structured pages to seamlessly switch between aggregate executive insights and raw operational data.
#### Page 1: Sales Insights Overview 📈
###### KPIs
 * **YTD Total Sales:** $371.2M *(Growth: +$70.8M / +23.59%)*
 * **MTD Total Sales:** $54.28M
 * **YTD Avg Price:** $28.0K *(Growth: -$0.22K / -0.79%)*
 * **MTD Avg Price:** $28.26k
 * **YTD Cars Sold:** 13K *(Growth: +2.616K / +19.73%)*
 * **MTD Cars Sold:** $13.26k
###### Slicers & Filters
 * **Navigation Toggle:** Menu (Overview / Details)
 * **Body Style Slicer** (SUV, Hatchback, Sedan, Passenger, Hardtop)
 * **Dealer Name Slicer**
 * **Transmission Slicer**
 * **Engine Slicer**
###### Visualizations
 * **YTD Sales Weekly Trend:** Area line chart plotting continuous structural sales volumes over a 50+ week cycle, flagging peak sales weeks (e.g., 14.9M peak).
 * **YTD Total Sales by Body Style:** Donut chart evaluating consumer demand distribution across Body Styles (SUV, Hatchback, Sedan, Passenger, Hardtop).
 * **YTD Total Sales by Color:** Donut chart mapping revenue variance driven by product aesthetics (Pale White, Black, Red).
 * **YTD Cars Sold by Dealer Region:** Bar chart sorting geographic performance across high-converting distribution regions (Austin: 2.3K, Janesville: 2.1K, Scottsdale: 1.9K, etc.).
 * **Company Wise Sales Trend Matrix:** Fully optimized heatmap data grid ranking auto manufacturers (Chevrolet, Ford, Dodge, Oldsmobile, Mercedes-B, etc.) by Avg Price, Cars Sold, Total Sales, and overall Contribution percentage (%GT YTD Total Sales).
###### Business Insights
 * **Macro Performance:** The company is showing strong transactional health with a +23.59% growth in YTD Sales, heavily supported by consistent distribution volumes (+19.73% cars sold).
 * **Pricing Strategy Variance:** Even though volume is scaling aggressively, the Average Pricing index dropped slightly (-0.79%), indicating potential margin compression or high-volume sales of lower-tier car models.
 * **Regional Dominance:** The Austin and Janesville logistics hubs are driving the maximum distribution footprint, making them prime targets for bulk inventory placement.
#### Page 2: Transaction Details Grid 🔍
###### Main Core KPI Ribbon (Synchronized cross-page tracking)
 * **YTD Total Sales:** $371.2M
 * **YTD Avg Price:** $28.0K
 * **YTD Cars Sold:** 13K
###### Slicers & Filters
 * **Navigation Toggle:** Menu (Overview / Details)
 * **Body Style Slicer**
 * **Dealer Name Slicer**
 * **Transmission Slicer**
 * **Engine Slicer**
###### Visualizations & Data Grid
 * **Granular Transaction Ledger:** A highly comprehensive operational table displaying individual rows tracking:
   * Car_id (Unique identifier sequences)
   * Date (Normalized calendar dates)
   * Customer Name (Buyer mapping parameters)
   * Dealer_Name (Specific retail facility names like *Buddy Storbeck's Diesel Service Inc*, *Classic Chevy*, etc.)
   * Company (Brand representation)
   * Color (Color mapping logs)
   * Model (Specific vehicle models like *Expedition*, *Durango*, *Eldorado*, *Malibu*)
   * Total Sales (Exact purchase value per record paired with an inline data bar visual for rapid sorting analysis)
###### Business Insights
 * **Audit-Ready Operations:** Allows operations managers to directly isolate specific underperforming models or investigate high-value transactions (e.g., Chevrolet Malibu driving an $82K high-impact purchase).
 * **Supply Chain Traceability:** Cross-references internal logistics dates with specific franchise dealers to measure delivery pipeline latency and floor-plan rotation efficiencies.
## Data Model & Transformation Logic 📐
 * Extensively utilized specialized Power Query functions to standardize string variations inside buyer profiles and dealership names.
 * Converted date strings into standardized regional date formats to enable DAX time-intelligence functions (TOTALYTD, TOTALMTD) to compile flawlessly without calculation exceptions.
### Author 👨‍💻
 * Ahmed Bux
