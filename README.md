# Mobile Sales Dashboard - Power BI Project
This repository hosts an advanced, interactive Mobile Sales Dashboard developed entirely in Microsoft Power BI Desktop. The dashboard transforms raw transactional data into a visual intelligence tool, designed to help sales managers, retail strategists, and analysts monitor and optimize mobile device sales performance.

## Project Goal
The primary objective is to provide a single-pane-of-glass view for tracking sales trends, product popularity, and customer behavior, enabling data-driven decisions regarding inventory, pricing, and promotional efforts.

## Dataset Used:
- <a href="https://github.com/Anuj122Mishra/Mobiles-Sales-Dashboard/blob/main/Mobile%20Sales%20Data.xlsx">Dataset</a>

## Key Features & Insights
### The dashboard offers deep insights through its interactive components and comprehensive visualizations:

### Key Performance Indicators (KPIs):
Instant visibility into crucial metrics like:

Total Sales (769M)

Total Quantity (19.15K)

Transactions (4K)

Average Price (40.11K)

Time Intelligence: Dynamic filtering capability including MTD (Month-to-Date) Report and Same Period Last Year comparisons, alongside a monthly breakdown.

User Interactivity: Custom slicers allow users to filter the entire report by Mobile Model, Payment Method, and Brand.

Geographical Analysis: Sales concentration visualized on a map showing Total Sales by City.

Performance Deep Dive: Analysis of Total Sales by Mobile Model and Total Sales by Brand to identify top performers.

Customer Insights: Visualization of customer Ratings and Transactions by Payment Method (UPI, Debit Card, Credit Card, Cash).

## Technologies and Skills Used
### This project leveraged a robust set of Microsoft BI tools and related analytical skills:

Microsoft Power BI Desktop: Served as the core development environment for all stages of the project, including data integration, modeling, visualization, and final report generation.

Power Query (M Language): Used extensively for the ETL process (Extract, Transform, Load). This involved advanced data cleaning (handling missing values), data shaping (merging and transforming tables), and performing necessary quality checks to prepare the raw data for the model.

DAX (Data Analysis Expressions): This skill was critical for creating complex, dynamic analytical measures. DAX was specifically used for implementing Time Intelligence calculations (e.g., MTD and Year-over-Year comparisons) and defining the custom Key Performance Indicators (KPIs) such as Total Sales and Average Price.

Data Modeling: Expertise was applied in structuring the underlying data by defining effective table relationships. This ensures high performance, efficiency, and accurate cross-filtering across all visuals in the dashboard.

Data Visualization & Report Design: Skills in data storytelling and UI/UX principles were employed to select and design the appropriate visuals (charts, maps, and slicers) to clearly communicate sales performance and trends to end-users.
## Process Steps
Data Acquisition: Connected Power BI to the raw mobile sales data sources.

Power Query (ETL): Utilized Power Query for the Extract, Transform, and Load (ETL) process:

Data Cleaning and Shaping: Handled missing values, standardized data types, and restructured tables.

Quality Check: Ensured data integrity before loading into the model.

Data Modeling: Established a robust data model by defining relationships between tables (e.g., Sales Fact table, Dimension tables).

DAX Calculations: Created calculated measures using DAX:

Defined core KPIs (Total Sales, Total Quantity, Transactions, Average Price).

Implemented Time Intelligence measures (MTD, Same Period Last Year).

Visualization Development: Built the dashboard visuals (Line charts, Bar charts, Map, Donut chart) to represent key insights (Sales by City, Quantity by Month, Ratings, etc.).

Interactivity Implementation: Integrated slicers (Mobile Model, Payment Method, Brand) and time selectors (MTD, Monthly filter) for user interaction.

Final Review: Conducted thorough testing to ensure filtering accuracy and data validation across the dashboard.
## Dashboard - <a href="https://github.com/Anuj122Mishra/Mobiles-Sales-Dashboard/blob/main/Mobile_Sales_Dashboard.png">View Dashboard</a>
<img width="1297" height="729" alt="Mobile_Sales_Dashboard" src="https://github.com/user-attachments/assets/06fe4675-f752-4098-9072-26d4209354fd" />

## Dashboard Impact and Use Cases
### This Mobile Sales Dashboard provides stakeholders with the critical intelligence needed to transition from reactive reporting to proactive strategy.

Optimized Inventory: By analyzing Total Quantity by Month and sales by Mobile Model, managers can accurately forecast demand, reducing overstocking or stockouts.

Targeted Marketing: Understanding Total Sales by City and Brand allows marketing teams to allocate advertising spend more effectively to high-performing regions and specific demographics.

Pricing Strategy: The Average Price metric, coupled with sales trends, helps in monitoring the effectiveness of pricing and promotional campaigns.

Customer Experience Improvement: Insights from the Ratings distribution and Transactions by Payment Method help identify service weak points and popular payment options, improving the customer checkout experience.
