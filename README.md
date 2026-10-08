# Finance_Analytics_Dashboard_Project-

A centralized, interactive Power BI analytical solution designed to track, monitor, and analyze financial transactions, customer behavior, and operational parameters across various business segments and geographic regions.

---

## 🎯 Short Description & Purpose

The purpose of this project is to solve data visibility challenges faced by the management team. This dashboard connects high-level financial KPIs with granular transactional details, allowing stakeholders to easily monitor business health, track operational leakage (failed transactions), analyze customer segments, and execute data-driven strategy adjustments.

---

## 🛠️ Tech Stack

* **Business Intelligence:** Power BI Desktop
* **Data Transformation & Modeling:** Power Query, DAX (Data Analysis Expressions)
* **Data Source Architecture:** Relational Transaction Database (Structured Transaction Logs)

---

## 📂 Data Source

The analytics engine processes a highly detailed transaction log ledger containing the following structural dimensions:
* **Transaction Core Data:** Unique Transaction ID, Execution Date, Category Type, and processing Status (Success/Failed/Pending).
* **Customer Profile Data:** Customer Name, Segment Profile (Retail, Premium, SME, etc.), Demographics (Gender), and Location (State).
* **Financial Ledger Metrics:** Transaction Amount, Operational Fees charged, and Government Taxes applied.

---

## ✨ Features & Highlights

* **Dynamic Metric Switching:** Built-in parameter toggle allowing users to swap the primary visual measure seamlessly across the report canvas.
* **Granular Cross-Filtering:** Comprehensive left-hand slicer panel supporting active sorting by Year, Occupation, and Business Category.
* **Seamless Page Navigation:** Integrated native UI buttons to quickly switch between aggregate overview metrics and deep-dive transactional lists.
* **Advanced Conditional Formatting:** Matrix tables utilize color gradients to instantly expose low and high-performing transaction types.

---

## 📊 Business Problems & Goal of Dashboard

### Business Problems Addressed:
* Difficulty in monitoring real-time transaction volumes and Year-over-Year (YoY) performance changes.
* Lack of visibility into which customer groups or regions generate the highest revenue margins.
* Inability to cleanly audit and isolate failed or pending transaction leaks.
* Scattered data tracking across transaction types, operational fee rules, and collected taxes.

### Strategic Goal:
To establish an intuitive, single source of truth dashboard that empowers executive leadership to identify high-potential states, optimize fee systems, minimize failed transaction friction, and make informed financial decisions.

---

## 🚶 Walkthrough by Visuals

### 1. High-Level KPI Summary (Top Ribbon)
* Displays instant counts for Total Amount, Total Transaction Count, Average Transaction Value, Fees, and Tax. 
* Every metric features integrated YoY variance labels showing growth or decline against the previous fiscal year.

### 2. Time-Series Trend Analysis (Line Chart)
* Evaluates monthly transaction volumes to track seasonal peaks and baselines throughout the calendar year.

### 3. Operational Allocation (Donut Chart)
* Provides a quick percentage-based split of Successful vs. Failed and Pending volume to assess operational stability.

### 4. Segment & Regional Breakdown (Horizontal Bar Charts)
* Features ranked distribution grids mapping financial performance across different Customer Segments and individual Indian States.

### 5. Profitability Matrix (Data Grid)
* Offers a cross-tabulated heatmap analysis mapping the count, amount, fee, and tax totals across distinct product types like Loans, Deposits, and Transfers.

---

## 💡 Business Impact & Insights (2024 Report)

* **Revenue Performance Concentration:** Total Transaction Amount stands at **₹135.62M**, representing a minor **1.06% YoY dip**. Volume is heavily anchored by the **Retail** segment (**₹74M**), leaving significant room to expand the lower-performing Wealth (₹6M) and Corporate (₹9M) footprints.
* **Regional Engine Drivers:** Out of all operational regions, **Maharashtra (₹19.7M)** and **Karnataka (₹15.8M)** emerge as the top regional revenue anchors, providing clear targets for localized marketing spend.
* **Seasonality Correction Opportunities:** Volume hits an annual trough in **February** before aggressively peaking in **May**. Operations can plan promotional campaigns in Q1 to flatten out this seasonal dip.
* **Operational Leakage Audit:** While the transaction success rate is healthy at **85.05%**, a **10.52% failure rate** accounts for **₹14.26M** in lost or blocked velocity, highlighting a critical tech infrastructure bottleneck to resolve.
* **High-Margin Value Streams:** Even though **Loan EMIs** and **Transfers** dominate the gross volume matrix (combining for over ₹75M), **Fees (₹217.16K)** and **Taxes (₹39.14K)** achieved positive growth trends, protecting overall operational margins.

---

## 📸 Screenshots

### Page 1: Overview Analysis Dashboard
https://github.com/Allamprabhu-creator/PowerBi_Dashboard_Project-/blob/main/Overview%20Analysis.PNG.png

### Page 2: Detailed Transaction Log Grid
https://github.com/Allamprabhu-creator/PowerBi_Dashboard_Project-/blob/main/Transactions.PNG.png
