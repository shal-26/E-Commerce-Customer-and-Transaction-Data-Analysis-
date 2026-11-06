# E-Commerce Customer and Transaction Data Analysis

## 1. Introduction
This project explores e-commerce customer and transaction data to uncover meaningful insights regarding purchasing behavior and sales performance. The analysis focuses on data cleaning, customer segmentation, and identifying seasonal trends to drive strategic business recommendations.

---

## 2. Environment & Setup
To replicate this analysis, ensure your environment meets the following requirements:
* **Language:** Python 
* **Environment:** Google Colab 

### Required Libraries:
* `pandas`: For data manipulation and cleaning.
* `numpy`: For numerical operations.
* `matplotlib` & `seaborn`: For data visualization and trend analysis.

---

## 3. How to Run the Analysis
1. **Open the Notebook:** Load the `.ipynb` file in Google Colab.
2. **Upload Datasets:** Upload the three raw data files (`customers.csv`, `products.csv`, and `transactions.csv`) into the session storage.
3. **Execute Cells:** Go to the top menu and select **Runtime > Run All**.
4. **Outputs:** Visualizations will appear directly within the notebook.

---

## 4. Tasks Summary

### Task 1: Data Cleaning & Exploration
* **Goal:** Prepare raw data for analysis.
* **Action:** Handled missing values (e.g., filled missing ages with the median) and converted date columns into the correct datetime format.
* **Output:** A clean, combined dataset merging customer profiles with their transaction history.

### Task 2: Customer Segmentation
* **Goal:** Categorize customers to enable targeted marketing.
* **Action:** Created a rule-based system to group customers. Identified **"High-Value Loyalists"** based on spend and frequency, and **"At Risk"** customers who haven't purchased in over 180 days.

### Task 3: Sales Analysis & Trends
* **Goal:** Identify high-performing products and seasonal patterns.
* **Action:** Aggregated revenue by category and resampled data to analyze monthly trends.
* **Insights:** Found that while Books drive the most traffic, the Home category drives the highest revenue. Also identified a significant drop in year-end sales.

### Task 4: Executive Summary (The Results)
* **Goal:** Communicate findings to non-technical stakeholders.
* **Action:** Summarized insights into a comprehensive report.
* **Recommendations:** Proposed holiday-themed cross-category bundles to address the year-end sales drop and a targeted re-engagement email campaign for "At Risk" customers.

---

## 5. Video Presentation
A complete walkthrough of the analytical approach, technical outputs, and final business recommendations is available below:

👉 **[Watch the Video Walkthrough](https://www.loom.com/share/42758aeba4e74703a8906ed7a34de1b8)**
