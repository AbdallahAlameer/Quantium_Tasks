# Quantium Retail Analytics: Customer Behavior & Store Trial Assessment

**Author:** Abdallah Alameer Ali
**Role:** Data Analyst

## 📌 Project Overview
This project is part of the Quantium Virtual Internship program. The primary objective is to analyze transaction and purchasing behavior data for a major retail client, evaluate the performance of targeted store trials (A/B testing), and deliver actionable commercial recommendations to the Category Manager to shape the upcoming strategic plan for the "Chips" category.

## 🛠️ Tech Stack & Tools
* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, SciPy (for statistical analysis)
* **Data Visualization & Reporting:** Matplotlib, Microsoft PowerPoint
* **Concepts:** Data Wrangling, Feature Engineering, A/B Testing, Control Store Selection, Data Storytelling (Pyramid Principle).

---

## 📂 Project Structure & Methodology

The project is divided into three main analytical tasks:

### Task 1: Data Preparation and Customer Analytics
* **Data Cleaning & Integration:** Merged transaction data (`QVI_transaction_data.xlsx`) with customer data (`QVI_purchase_behaviour.csv`). Handled data inconsistencies, date formatting, and removed outliers (e.g., bulk wholesale purchases).
* **Feature Engineering:** Extracted `PACK_SIZE` and standardized `BRAND` names using text analysis on the product descriptions. Filtered out non-chip products (e.g., salsa).
* **Exploratory Data Analysis (EDA):** Grouped data by customer lifestage and affluence (`PREMIUM_CUSTOMER`) to identify key purchasing behaviors.
* **Key Finding:** Identified that **Budget Older Families** and **Mainstream Young Singles/Couples** are the most profitable segments and drive the highest volume of sales.

### Task 2: Experimentation and Uplift Testing (A/B Testing)
* **Objective:** Evaluate the impact of a new store layout implemented in three trial stores (77, 86, and 88) during February to April 2019.
* **Control Store Selection:** Developed a custom algorithm to match each trial store to a control store based on historical performance. The selection metric combined **Pearson Correlation** and **Magnitude Distance** across monthly total sales and customer counts.
  * Store 77 was matched with Control Store 233.
  * Store 86 was matched with Control Store 155.
  * Store 88 was matched with Control Store 237.
* **Performance Assessment:** Calculated a 95% confidence interval based on the control stores' scaled performance to determine if the trial stores showed a statistically significant uplift during the trial period.
* **Key Finding:** Stores 77 and 88 showed a statistically significant increase in total sales. Store 86 showed an increase in customer traffic, though overall revenue was likely offset by promotional pricing.

### Task 3: Analytics and Commercial Application
* **Data Storytelling:** Translated complex statistical findings into a clear, concise executive report.
* **Framework:** Applied the **Pyramid Principle** to structure the presentation, prioritizing the main recommendations and key insights upfront for C-level executives.
* **Deliverable:** A polished presentation outlining the category overview, the success of the store trials, and strategic next steps, accompanied by a professional cover email to the client.

---

## 💡 Executive Recommendations
1. **Rollout Successful Layouts:** Expand the trial layouts from Stores 77 and 88 to the broader store network, as they demonstrably increase chip sales.
2. **Optimize Shelf Space:** Dedicate more shelf space and promotional focus to 175g and 150g pack sizes of Kettle and Smiths brands, directly targeting the high-revenue "Older Families" segment.
3. **Refine Promotional Strategy:** Investigate the pricing and promotional mechanisms at Store 86 to ensure that increased customer traffic effectively translates into higher overall revenue.
