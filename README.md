
# Sales Data Analysis

This project provides a comprehensive analysis of sales data using Python's `pandas`, `matplotlib`, and `seaborn` libraries. The goal is to uncover key business insights through clean and informative visualizations.

---

## Table of Contents
- [Overview](#overview)
- [Dataset Description](#dataset-description)
- [Visualizations](#visualizations)
  - [Monthly Sales Trend](#1-monthly-sales-trend)
  - [Sales by Product Line](#2-sales-by-product-line)
  - [Sales by Deal Size](#3-sales-by-deal-size)
- [Key Takeaways](#key-takeaways)
- [Technologies Used](#technologies-used)
- [How to Use](#how-to-use)
- [License](#license)

---

## Overview

This analysis aims to transform raw sales data into actionable insights. It focuses on answering essential business questions such as:

- What are the monthly trends in sales?
- Which product lines generate the most revenue?
- How does deal size impact average order value?

---

## Dataset Description

The dataset contains information on customer orders including:

- Order details: `ORDERNUMBER`, `ORDERDATE`, `SALES`, `QUANTITYORDERED`, `PRICEEACH`
- Product info: `PRODUCTLINE`, `PRODUCTCODE`
- Customer and location: `CUSTOMERNAME`, `CITY`, `COUNTRY`
- Sales status and deal size: `STATUS`, `DEALSIZE`

---

## Visualizations

### 1. Monthly Sales Trend

A time series line chart to observe how sales fluctuate month-over-month, helping identify seasonal patterns and performance dips.

### 2. Sales by Product Line

A horizontal bar chart showing total sales by product category, highlighting top-performing product lines.

### 3. Sales by Deal Size

A bar chart illustrating average sales value per order based on deal size (Small, Medium, Large), useful for evaluating customer order behavior.

---

## Key Takeaways

- **Monthly Trends:** Identify peak sales months and plan marketing strategies accordingly.
- **Top Products:** Focus marketing efforts and inventory planning around high-revenue product lines.
- **Deal Insights:** Tailor sales strategy based on which deal sizes yield higher returns.

---

## Technologies Used

- **Python** (v3.8+)
- **Pandas** for data manipulation
- **Matplotlib** & **Seaborn** for data visualization
- **Jupyter Notebook** for interactive analysis

---

## How to Use

1. Download and open the `Sales_Data_Analysis.ipynb` file in Jupyter Notebook.
2. Run each cell sequentially to generate the visualizations and insights.
3. Ensure the dataset `sales_data_sample.csv` is in the same directory or update the path accordingly.

---

## License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).

---
