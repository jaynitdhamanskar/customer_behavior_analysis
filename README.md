# Customer Behavior Data Analytics Project

## Overview

This project demonstrates an end-to-end data analytics workflow, covering data ingestion, exploration, transformation, querying, visualization, and reporting. The objective is to analyze customer shopping behavior and generate actionable business insights using Python, SQL, and Power BI. The project is designed to reflect real-world analytics practices and is suitable for stakeholder reporting as well as recruiter review.

---

## Dataset

The dataset contains customer shopping and transaction-level information, including:

* Customer demographics (age group, gender)
* Subscription status
* Purchase amounts
* Product categories
* Payment methods
* Shipping types
* Seasonal and discount indicators

The data is structured to support both exploratory analysis and business intelligence reporting.

---

## Tools & Technologies

* **Python**: Data loading, cleaning, and exploratory data analysis (EDA)

  * Libraries: Pandas, NumPy, Matplotlib, Seaborn
* **SQL (PostgreSQL)**: Data querying, aggregation, and validation
* **Power BI**: Interactive dashboard creation and KPI visualization
* **Gamma**: Presentation (PPT) creation for executive-level storytelling
* **Jupyter Notebook**: Analysis and documentation

---

## Project Workflow / Steps

### 1. Data Loading

* Imported raw dataset into Python using Pandas
* Performed initial inspection to understand schema, data types, and missing values

### 2. Exploratory Data Analysis (EDA)

* Analyzed customer distribution by age group, gender, and subscription status
* Explored purchase trends by category, payment method, and season
* Identified patterns in discounts and revenue contribution

### 3. Data Cleaning & Preparation

* Handled missing and inconsistent values
* Standardized categorical fields (e.g., payment methods, shipping types)
* Validated numerical fields such as purchase amount and ratings
* Prepared clean datasets for SQL and Power BI consumption

### 4. SQL Analysis (PostgreSQL)

* Loaded cleaned data into a PostgreSQL database
* Wrote SQL queries to:

  * Aggregate revenue by category and season
  * Analyze subscription vs non-subscription behavior
  * Validate KPIs used in the dashboard
* Ensured consistency between Python analysis and SQL outputs

### 5. Power BI Dashboard

* Built an interactive dashboard with slicers and filters
* Key visuals include:

  * Customer and revenue KPIs
  * Subscription distribution
  * Payment method share
  * Revenue by category and age group
  * Seasonal revenue and discount impact
* Designed for easy exploration by business users

### 6. Reporting & Presentation

* Created a structured analytical report summarizing insights and business implications
* Developed a presentation (PPT) using Gamma to communicate findings to stakeholders
* Focused on clarity, storytelling, and decision-oriented insights

---

## Dashboard

The Power BI dashboard provides a single-page view of customer behavior and revenue drivers. It supports:

* Drill-down analysis using filters
* Comparison across customer segments
* Identification of high-performing categories and seasons

The dashboard is suitable for leadership reviews and ongoing performance monitoring.

---

## Key Results & Insights

* Majority of customers are non-subscribers, indicating strong potential for recurring revenue growth
* Clothing is the top revenue-generating category
* Young Adult and Middle-Aged customers contribute the highest revenue
* Discounts significantly impact seasonal revenue, especially during Fall and Winter
* Payment preferences are diversified, requiring multiple checkout options

---

## How to Run the Project

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   ```

2. **Set up Python environment**

   ```bash
   pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2
   ```

3. **Run the Jupyter Notebook**

   * Open the notebook
   * Execute cells in sequence to perform EDA and data cleaning

4. **Set up PostgreSQL**

   * Create a database
   * Load the cleaned dataset into PostgreSQL
   * Run the provided SQL queries for analysis

5. **Open Power BI Dashboard**

   * Connect Power BI to the cleaned dataset or PostgreSQL database
   * Refresh data and explore the dashboard

6. **Review Report & Presentation**

   * Refer to the analytical report for detailed insights
   * Use the Gamma-generated PPT for stakeholder communication

---
