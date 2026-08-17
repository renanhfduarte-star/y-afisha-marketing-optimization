# Optimizing Marketing Expenses for Y.Afisha

This repository contains a data analysis project focused on optimizing marketing expenses for an entertainment ticketing platform.

## Project Overview

The main objective of this project is to analyze the marketing expenses of Y.Afisha and provide data-driven recommendations on how to reallocate the marketing budget to maximize profitability. Through the analysis of server logs, sales data, and marketing costs from January 2017 to December 2018, this project uncovers user behavior patterns, calculates key unit economics, and identifies the most profitable customer cohorts.

## Tools & Technologies

*   **Python:** Data manipulation and analysis.
*   **Pandas & NumPy:** Data cleaning, grouping, and cohort analysis.
*   **Matplotlib & Seaborn:** Data visualization and heatmap generation.
*   **Jupyter Notebook:** Interactive development and reporting.
*   **Key Analytical Concepts:** Cohort Analysis, Unit Economics, Conversion Funnels.

## Key Metrics Analyzed

The analysis evaluates three main business areas:
*   **Product Metrics:** DAU, WAU, MAU (Daily, Weekly, and Monthly Active Users), and ASL (Average Session Length).
*   **Sales Metrics:** Time to Conversion (how long it takes for a user to make their first purchase) and AOV (Average Order Value).
*   **Marketing & Financial Metrics:** CAC (Customer Acquisition Cost), LTV (Lifetime Value), and ROMI (Return on Marketing Investment).

## Key Findings

| Insight Category | Key Finding |
| :--- | :--- |
| **Short Conversion Window** | The Average Session Length is under 100 seconds, and almost all buyers convert within the first few days. |
| **The September 2017 Anomaly** | The cohort from September 2017 is an absolute outlier, breaking even in just 3 months and reaching a ROMI of 1.42. |
| **Declining Recent Cohorts** | Cohorts from early 2018 show a dropping AOV and very low Cumulative ROMI. |

## Strategic Recommendations

*   **Immediate Retargeting:** Aggressively focus retargeting campaigns (such as push notifications and discounts) within the first 24-48 hours, given the extremely short user conversion window.
*   **Replicate Past Success:** Deep dive into the specific traffic sources and campaigns active during September 2017 to understand and replicate the specific factors that drove its exceptional Return on Marketing Investment.
*   **Budget Reallocation:** Re-evaluate and potentially cut funding for the worst-performing traffic sources of early 2018 to stop the financial bleed, reallocating those resources to historically high-performing channels.

## Repository Contents

*   `project_y_afisha.ipynb`: The main Jupyter Notebook containing the full analysis, code, and visualizations.
*   `datasets/`: Folder containing the raw data (`visits_log_us.csv`, `orders_log_us.csv`, `costs_us.csv`).

---
This project was completed by Renan Henrique Duarte Ferreira as part of a Data Analytics curriculum.