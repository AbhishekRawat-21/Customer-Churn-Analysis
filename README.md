# 📊 Customer Churn Analysis using SQL & Python

## 📌 Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses. Understanding why customers leave helps organizations improve customer retention, increase customer satisfaction, and maximize revenue.

This project presents an end-to-end customer churn analysis using **SQLite, SQL, Python, Pandas, NumPy, Matplotlib, and Seaborn**.

The analysis follows the complete Data Analytics workflow:

- Data Loading
- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis (EDA)
- SQL Analysis
- Data Visualization
- Business Insights

The objective of this project is to transform raw customer data into meaningful business insights that support data-driven decision-making.


---

## 🛠️ Tools & Technologies

| Category | Tools |
|----------|-------|
| Programming Language | Python, SQL |
| Database | SQLite |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Development Environment | Jupyter Notebook |
| Version Control | Git & GitHub |


---

## 📂 Dataset

This project uses a **synthetic customer churn dataset** stored in a SQLite database (`customer_churn.db`).

The database contains **1,500 customer records** distributed across three related tables.

### Database Tables

| Table Name | Description |
|------------|-------------|
| `db_customer` | Stores customer demographic and personal information. |
| `db_subscription` | Stores subscription details, billing information, churn status, and Customer Lifetime Value (CLTV). |
| `db_support` | Stores customer support interactions, complaints, and Customer Satisfaction (CSAT) records. |

The data from these three tables was loaded, cleaned, transformed, and analyzed using SQL and Python to generate business insights.


---

## 🔄 Project Workflow

This project follows a complete end-to-end Data Analytics workflow:

1. Import required Python libraries.
2. Connect to the SQLite database.
3. Load data from multiple tables.
4. Perform data cleaning and preprocessing.
5. Apply feature engineering.
6. Conduct Exploratory Data Analysis (EDA).
7. Analyze business problems using SQL queries.
8. Create visualizations using Matplotlib and Seaborn.
9. Generate business insights.
10. Summarize findings and conclusions.

---

## 📁 Repository Structure

```text
customer-churn-analysis/
│
├── data/
│   └── customer_churn.db
│
├── notebooks/
│   └── customer-churn-analysis.ipynb
│
├── images/
│   ├── gender_distribution.png
│   ├── churn_distribution.png
│   ├── customer_distribution_by_plan.png
│   ├── monthly_charges_distribution.png
│   ├── cltv_box_plot.png
│   ├── correlation_heatmap.png
│   └── yearly_subscription_trend.png
│
├── README.md
├── requirements.txt
└── .gitignore
```


## 📈 Visualizations

### 1. Gender Distribution

Shows the distribution of customers by gender.

![Gender Distribution](images/gender_distribution.png)

---

### 2. Customer Churn Distribution

Shows the proportion of churned and active customers.

![Customer Churn Distribution](images/churn_distribution.png)

---

### 3. Customer Distribution by Plan

Shows how customers are distributed across different subscription plans.

![Customer Distribution by Plan](images/customer_distribution_by_plan.png)













