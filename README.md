# Superstore Sales Performance Dashboard (Power BI)

An interactive Power BI dashboard analyzing sales, profitability, and customer behavior for the Sample Superstore dataset — built to surface trends across time, region, product, and city, and to support quick, filterable business reporting.

<img width="981" height="561" alt="dashboard-preview" src="https://github.com/user-attachments/assets/cd1985d1-40ea-4741-8afc-2242f01e5f6a" />

# Overview

This dashboard answers four core business questions:

* How are orders and sales trending over time (year over year and month over month)?
* Which regions and cities generate the most sales, and how do orders compare?
* Which products and cities are the top revenue drivers?
* How does profit track alongside sales on a monthly basis?

### Key Metrics (KPI Cards)
|  Metric      |  Value    |
|  ----------  |  -------  |
|Total Cities  |	531      |
|Total Orders   |  5.0K     |
|Total Customers|	793      |
|Quantity Sold  |  37.9K    |
|Total Sales    |  2.3M     |
|Profit Margin %|	12.5%    |
|Average Order Value |	₹459 |

### Dashboard Pages & Visuals
+ **Annual Orders & Sales Trend** — combo chart (bar + line) showing order count and sales by year, 2014–2017
+ **Monthly Orders & Sales Trend** — combo chart showing seasonality across months, with a clear peak heading into Q4
+ **Regional Sales & Order Analysis** — combo chart comparing sales and order count across South, Central, East, and West regions
+ **Top 10 Products by Sales** — horizontal bar chart ranking best-selling products
+ **Top 10 Cities by Sales** — horizontal bar chart ranking top revenue cities, led by New York City
+ **Monthly Sales & Profit Trend** — dual-line chart tracking sales against profit month over month
+ **Filters** — slicers for Order Year, Order Month, Quarter, and City, so every visual on the page can be cross-filtered together

### Data Model

Built on the Sample - Superstore dataset, with the following DAX measures and calculated columns:

#### Measures

+ Total Sales
+ Total Orders
+ Total Customers
+ Total Cities
+ Total Quantity
+ Profit Margin %
+ AOV (Average Order Value)

### Calculated Columns

+ Order_Year
+ Order_Month
+ Quarter

### Tools Used
+ Power BI Desktop (data modeling, DAX, report design)
+ Power Query (data shaping/cleaning)

### Repository Contents

|  File  |	Description |
| ------ | ------------ |
|  PowerBI_Superstore_Sales_Analysis.pbix  |  Full Power BI report file — data model, measures, and dashboard |
|  docs/dashboard-preview.png  |  Static preview image of the dashboard (used above) |

### How to Use
1. Download PowerBI_Superstore_Sales_Analysis.pbix and open it in Power BI Desktop (free).
2. Use the Order Year, Order Month, Quarter, and City slicers at the bottom of the report to filter every visual at once.
3. Hover over any chart for detailed tooltips.

### Key Insights

+ Sales and order volume grew consistently from 2014 to 2017, with the sharpest acceleration in the final year.
+ Demand is seasonal: sales dip in February and climb steadily toward a Q4 peak (September–November).
+ The West region leads in both sales and order volume; South trails behind the other three regions.
+ New York City and Los Angeles are the top two revenue-generating cities by a clear margin.
+ Sales and profit trend closely together month to month, suggesting a fairly stable margin rather than isolated high/low-margin spikes.

### Skills Demonstrated
Data modeling · DAX measures · Power Query · interactive dashboard design · time-series and regional analysis · business storytelling with data
