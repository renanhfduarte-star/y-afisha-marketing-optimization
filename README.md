# 📊 Optimizing Marketing Expenses for Y.Afisha

## 📝 Project Overview
This project was developed as part of the TripleTen Data Analytics Bootcamp. The main objective is to analyze the marketing expenses of **Y.Afisha**, an entertainment ticketing platform, and provide data-driven recommendations on how to reallocate the marketing budget to maximize profitability.

Through the analysis of server logs, sales data, and marketing costs from January 2017 to December 2018, this project uncovers user behavior patterns, calculates key unit economics, and identifies the most profitable customer cohorts.

## 🛠️ Tools and Technologies Used
* **Python:** Data manipulation and analysis.
* **Pandas & NumPy:** Data cleaning, grouping, and cohort analysis.
* **Matplotlib & Seaborn:** Data visualization and heatmap generation.
* **Jupyter Notebook:** Interactive development and reporting.
* **Key Analytical Concepts:** Cohort Analysis, Unit Economics, Conversion Funnels.

## 📈 Key Metrics Analyzed
The analysis is divided into three main business areas:

1. **Product Metrics:**
   * **DAU, WAU, MAU** (Daily, Weekly, and Monthly Active Users).
   * **ASL** (Average Session Length).
2. **Sales Metrics:**
   * **Time to Conversion:** How long it takes for a user to make their first purchase.
   * **AOV** (Average Order Value).
3. **Marketing & Financial Metrics:**
   * **CAC** (Customer Acquisition Cost).
   * **LTV** (Lifetime Value).
   * **ROMI** (Return on Marketing Investment).

## 💡 Key Business Insights & Recommendations
* **Short Conversion Window:** The Average Session Length is under 100 seconds, and almost all buyers convert within the first few days. **Recommendation:** Aggressively focus retargeting campaigns (push notifications, discounts) within the first 24-48 hours.
* **The September 2017 Anomaly:** The cohort from September 2017 is an absolute outlier, breaking even in just 3 months and reaching a ROMI of 1.42. **Recommendation:** Deep dive into the specific traffic sources and campaigns active during this month to replicate their success.
* **Cut Losses on Recent Cohorts:** Cohorts from early 2018 show a dropping AOV and very low Cumulative ROMI. **Recommendation:** Re-evaluate and potentially cut funding for the worst-performing traffic sources of 2018 to stop the financial bleed.

## 📂 Project Structure
* `project_y_afisha.ipynb` - The main Jupyter Notebook containing the full analysis, code, and visualizations.
* `datasets/` - Folder containing the raw data (note: data files might be ignored via `.gitignore` depending on size).
  * `visits_log_us.csv`
  * `orders_log_us.csv`
  * `costs_us.csv`

## 🚀 How to Run the Project
1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/renanhfduarte-star/y-afisha-marketing-optimization.git](https://github.com/renanhfduarte-star/y-afisha-marketing-optimization.git)