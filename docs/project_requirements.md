# User Story | Sales & Customer Performance Dashboards

## Introduction
This user story outlines the specifications for building two Tableau dashboards designed to help stakeholders—such as sales managers, marketing teams, and executives—analyze sales performance and customer behavior.  
The dashboards aim to support data-driven decision-making through clear KPIs, trends, and interactive exploration.

---

## Sales Dashboard | Requirements

### Dashboard Purpose
The purpose of the Sales Dashboard is to provide a high-level overview of sales performance, enabling stakeholders to analyze year-over-year results and identify key sales trends.

### Key Requirements

#### KPI Overview
- Display a summary of:
  - Total Sales  
  - Total Profit  
  - Total Quantity Sold  
- Show values for both the **current year** and the **previous year**.

#### Sales Trends
- Present monthly trends for each KPI for:
  - Current year
  - Previous year
- Clearly identify and highlight:
  - Months with the highest sales
  - Months with the lowest sales

#### Product Subcategory Comparison
- Compare sales performance across product subcategories for:
  - Current year
  - Previous year
- Include a comparison between:
  - Sales
  - Profit

#### Weekly Trends for Sales & Profit
- Present weekly sales and profit data for the current year.
- Display average weekly values.
- Highlight:
  - Weeks above the average
  - Weeks below the average  
  to draw attention to performance patterns.

---

## Customer Dashboard | Requirements

### Dashboard Purpose
The Customer Dashboard provides an overview of customer data, trends, and behaviors.  
It supports marketing teams and management in understanding customer segments, loyalty, and opportunities to improve customer satisfaction.

### Key Requirements

#### KPI Overview
- Display a summary of:
  - Total Number of Customers
  - Total Sales per Customer
  - Total Number of Orders
- Show values for both the **current year** and the **previous year**.

#### Customer Trends
- Present monthly trends for each KPI for:
  - Current year
  - Previous year
- Clearly identify and highlight:
  - Months with the highest sales
  - Months with the lowest sales

#### Customer Distribution by Number of Orders
- Visualize the distribution of customers based on the number of orders placed.
- Provide insights into:
  - Customer behavior
  - Loyalty
  - Engagement levels

#### Top 10 Customers by Profit
- Display the top 10 customers ranked by profit contribution.
- Include the following attributes:
  - Rank
  - Number of Orders
  - Current Sales
  - Current Profit
  - Last Order Date

---

## Design & Interactivity Requirements

### Dashboard Dynamics
- Allow users to analyze historical data by selecting any desired year.
- Enable easy navigation between the Sales and Customer dashboards.
- Make charts and visuals interactive so users can filter data directly through the dashboard.

### Data Filters
- Allow filtering by product attributes:
  - Category
  - Subcategory
- Allow filtering by geographic attributes:
  - Region
  - State
  - City
