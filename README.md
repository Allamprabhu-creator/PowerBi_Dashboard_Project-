# Finance Analytics Dashboard Project

A centralized, interactive Power BI dashboard designed to track, monitor, and analyze financial transactions, customer behavior, and operational performance across business segments. The dashboard brings together key financial KPIs and transaction-level insights into a single reporting layer to support faster, more informed business decisions.

---

## Overview

This project addresses a common business challenge: fragmented financial data. Management teams often struggle to connect high-level revenue trends with transaction-level activity, making it difficult to understand performance drivers, identify operational risks, and prioritize action areas.

This dashboard consolidates transaction, customer, and financial metrics into an executive-friendly interface that helps stakeholders:

- monitor revenue growth and transaction trends
- evaluate customer and regional performance
- identify failed or pending transaction bottlenecks
- analyze fee and tax contribution by category
- compare current performance against prior-year benchmarks

---

## Business Objective

The primary goal of this project is to create a single source of truth for financial performance analysis. It enables leadership to identify high-value states, optimize fee structures, reduce failed transaction friction, and make data-backed decisions across product lines and customer segments.

---

## Tech Stack

* **Business Intelligence:** Power BI Desktop
* **Data Transformation & Modeling:** Power Query, DAX
* **Data Source Architecture:** Relational transaction database

---

## Data Source

The dashboard uses a detailed transaction ledger that includes the following dimensions:

* **Transaction Core Data:** Transaction ID, execution date, category, and status (Success/Failed/Pending)
* **Customer Profile Data:** Customer name, segment, gender, and state
* **Financial Ledger Metrics:** Transaction amount, operational fees, and government taxes

This structured dataset enables multi-dimensional analysis across time, geography, customer groups, and product categories.

---

## Key Features

* **Dynamic Metric Switching:** Users can switch the primary measure across the report canvas based on analysis needs.
* **Granular Cross-Filtering:** A left-side slicer panel supports filtering by year, occupation, and business category.
* **Seamless Page Navigation:** Built-in navigation buttons allow quick switching between summary and detail views.
* **Advanced Conditional Formatting:** Matrix visuals use color gradients to emphasize strong and weak performance patterns.
* **Trend and Performance Analysis:** KPI and time-series visuals help track seasonality and year-over-year movement.
* **Operational Monitoring:** Transaction status distribution helps identify failed and pending transaction risks.

---

## Dashboard Structure

### 1. High-Level KPI Summary
This section provides an at-a-glance view of:

* total transaction amount
* total transaction count
* average transaction value
* fee revenue
* tax revenue
* YoY variance values

### 2. Time-Series Trend Analysis
A monthly trend view helps monitor seasonal patterns and identify performance peaks and low points throughout the year.

### 3. Operational Allocation
This section shows the proportion of successful, failed, and pending transactions, helping teams assess operational stability and service performance.

### 4. Segment & Regional Breakdown
The dashboard highlights performance by:

* customer segment
* state/region
* business category

This helps identify the strongest contributors to revenue and where intervention may be needed.

### 5. Profitability Matrix
A cross-tabbed matrix compares transaction count, amount, fee, and tax across categories such as loans, deposits, and transfers.

---

## Business Problems Addressed

* Difficulty tracking transaction volumes and year-over-year performance changes
* Limited visibility into the customer groups and regions driving revenue
* Inability to isolate failed or pending transaction issues efficiently
* Disconnected tracking across transaction types, fee structures, and tax data

---

## Strategic Goal

To create an intuitive, single-source dashboard that helps leadership identify high-potential regions, optimize fee systems, minimize transaction leakage, and strengthen financial decision-making across the business.

---

## Business Impact & Insights (2024 Report)

* **Revenue Performance Concentration:** Total transaction amount reached **₹135.62M**, showing a minor **1.06% YoY decline**. The **Retail** segment contributed the largest share, accounting for **₹74M**.
* **Regional Engine Drivers:** **Maharashtra (₹19.7M)** and **Karnataka (₹15.8M)** emerged as the top regional revenue contributors, highlighting clear opportunities for targeted expansion and local strategy.
* **Seasonality Correction Opportunities:** Transaction volume dipped in **February** before peaking in **May**, indicating strong seasonal variation that could be managed through better planning.
* **Operational Leakage Audit:** While the success rate remained healthy at **85.05%**, the **10.52% failure rate** represented approximately **₹14.26M** in blocked or lost transaction value.
* **High-Margin Value Streams:** Loan EMIs and transfers dominated the overall transaction matrix, while fees and taxes also showed strong contribution potential across high-volume categories.

---

## Screenshots

### Page 1: Overview Analysis Dashboard
![Overview Analysis Dashboard](https://github.com/Allamprabhu-creator/PowerBi_Dashboard_Project-/blob/main/Overview%20Analysis.PNG.png)

### Page 2: Detailed Transaction Log Grid
![Detailed Transaction Log Grid](https://github.com/Allamprabhu-creator/PowerBi_Dashboard_Project-/blob/main/Transactions.PNG.png)

---

## How to Use

1. Open the project in Power BI Desktop.
2. Refresh the data source connection.
3. Navigate through the overview, trend, operational, and detailed transaction pages.
4. Use slicers and filters to segment analysis by year, category, region, and customer profile.
5. Review KPI cards and matrix visuals to identify trends and operational risks.

---

## Future Enhancements

Potential improvements for future versions include:

- integration with live or automated data refreshes
- more detailed drill-through pages
- risk and compliance tracking views
- executive summary export features
- scenario-based financial analysis

---

## Conclusion

This project demonstrates a practical business intelligence solution for financial monitoring and decision support. By combining transaction, customer, and operational data in a single Power BI dashboard, it enables stronger visibility, better analysis, and more confident business action.
