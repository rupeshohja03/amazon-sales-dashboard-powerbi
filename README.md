# Amazon Sales Dashboard (Power BI)

Interactive Power BI dashboard analyzing Amazon product sales — YTD/QTD tracking, category performance, and top products by sales and reviews.


DASHBOARD:- ()<img width="1329" height="743" alt="Amazon_Dashboard" src="https://github.com/user-attachments/assets/bd153ecd-506f-4f22-b7ac-6f2626d9e89b" />

## 📌 Overview

This project is an end-to-end Power BI dashboard built to analyze Amazon product sales performance. It covers the full analytics workflow — importing and cleaning raw sales data from a CSV source, modeling the data, building DAX measures for time-intelligence and KPI calculations, and designing an interactive report with charts, cards, and slicers.

| | |
|---|---|
| **Tool Used** | Microsoft Power BI (Power Query, Data Model, DAX, Report View) |
| **Data Source** | Amazon product sales data (CSV file) |
| **Project Type** | Sales performance / retail analytics dashboard |
| **Core Focus** | YTD & QTD sales tracking, product performance, customer review analysis |

## 🎯 Problem Statement

The dashboard was built to answer the following KPI requirements:

- **YTD Sales** – Monitor year-to-date sales to gauge overall revenue performance over time.
- **QTD Sales** – Track quarter-to-date sales figures to identify sales trends and fluctuations.
- **YTD Products Sold** – Analyze the total number of products sold throughout the year.
- **YTD Reviews** – Keep tabs on year-to-date product reviews to assess customer feedback.

## 📊 Visualizations

- **Sales by Month** (Line Chart) – monthly sales trend and seasonality
- **Sales by Week** (Column Chart) – short-term fluctuations
- **Sales by Product Category** (Table) – category-wise sales breakdown
- **Top 5 Products by YTD Sales** (Bar Chart)
- **Top 5 Products by YTD Reviews** (Bar Chart)
- Slicers for **Product Category** and **Quarter**

## 🛠️ Skills & Functionalities Applied

`Power Query` · `Data Cleaning` · `Data Modelling` · `Date Tables` · `Time Intelligence Functions` · `DAX` · `CALCULATE` · `YTD/QTD Functions` · `Filter Function` · `Text & Date Functions` · `Conditional Formatting` · `Custom Sorting` · `Card Visuals` · `Chart Creation` · `Navigation`

## 📈 Key Results

| KPI | Value |
|---|---|
| YTD Sales | **$2.2M** |
| QTD Sales | **$811.09K** |
| YTD Products Sold | **27.75K** |
| YTD Reviews | **19.42M** |

**Top category:** Men Shoes (43.18% of YTD sales)
**Top product by sales:** Nikon Wide Angle AF Nikkor 24mm lens (~$34K)
**Top product by reviews:** SanDisk 16GB 3-Pack Ultra microSDHC (0.40M reviews)

## 💡 Insights

- Revenue is concentrated in a few categories — Men Shoes and Camera together drive nearly two-thirds of YTD sales.
- Sales are highly seasonal, peaking between September and November.
- High review volume relative to units sold reflects strong customer engagement.

## 📁 Repository Structure
amazon-sales-dashboard-powerbi/
├── screenshots/
│ └── dashboard.png
├── Amazon_Sales_Dashboard.pbix
└── README.md


## 🚀 How to Use

1. Clone this repository
2. Open `Amazon_Sales_Dashboard.pbix` in Power BI Desktop
3. Refresh the data source if needed
4. Explore the dashboard using the Category and Quarter slicers
