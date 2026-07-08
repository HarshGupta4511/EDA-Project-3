# 🛍️ Customer Behavior & Satisfaction Analysis using Python | Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs an **Exploratory Data Analysis (EDA)** on an e-commerce customer dataset to understand customer behavior, spending patterns, purchasing habits, and the factors associated with customer satisfaction.

The analysis follows a structured EDA workflow, beginning with data understanding and cleaning, followed by **Univariate**, **Bivariate**, and **Multivariate** analyses to uncover meaningful business insights.

---

## 🎯 Objectives

* Understand customer demographics and purchasing behavior.
* Analyze customer satisfaction across different customer segments.
* Identify factors associated with higher customer spending.
* Explore purchasing patterns across membership types.
* Generate business insights from customer behavior.

---

## 📂 Dataset Features

The dataset contains information related to customers, including:

* Customer ID
* Gender
* Age
* City
* Membership Type
* Total Spend
* Items Purchased
* Average Rating
* Discount Applied
* Days Since Last Purchase
* Satisfaction Level

---

## 📊 Analysis Performed

### 1. Data Understanding

* Dataset Overview
* Data Types
* Missing Values
* Duplicate Records
* Statistical Summary

---

### 2. Data Cleaning

* Verified missing values
* Checked duplicate records
* Validated categorical values
* Prepared the dataset for analysis

---

### 3. Univariate Analysis

Individual feature analysis was performed to understand the distribution of every variable.

Topics covered include:

* Gender Distribution
* Membership Distribution
* Customer Distribution by City
* Satisfaction Level Distribution
* Discount Usage
* Age Distribution
* Total Spending Distribution
* Items Purchased Distribution
* Customer Rating Distribution
* Days Since Last Purchase

---

### 4. Bivariate Analysis

The primary business question explored was:

> **What factors are associated with customer satisfaction?**

Relationships analyzed include:

* Gender vs Satisfaction
* City vs Satisfaction
* Membership vs Satisfaction
* Discount Applied vs Satisfaction
* Age vs Satisfaction
* Total Spend vs Satisfaction
* Items Purchased vs Satisfaction
* Average Rating vs Satisfaction
* Days Since Last Purchase vs Satisfaction

---

### 5. Multivariate Analysis

Multiple variables were analyzed simultaneously to better understand customer behavior.

Analyses include:

* Membership Type × Total Spend × Satisfaction
* Items Purchased × Total Spend × Satisfaction
* Age × Total Spend × Satisfaction

---

## 📈 Key Insights

* Gold members exhibit the highest satisfaction levels.
* Bronze membership customers report comparatively lower satisfaction.
* Customers from Chicago and Miami have the highest proportion of dissatisfied responses.
* Satisfied customers generally:

  * Spend more
  * Purchase more items
  * Give higher ratings
  * Return to the platform sooner
* Customers aged approximately **28–31 years** appear to be among the most engaged customer group.

---

## 🛠️ Libraries Used

* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 📁 Repository Structure

```text
├── Customer_Behavior_Analysis_EDA.ipynb
├── README.md
└── Dataset.csv
```

---

## 🚀 How to Run

1. Clone this repository.

```bash
git clone <repository-url>
```

2. Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open the notebook using Jupyter Notebook or JupyterLab.

4. Run all cells sequentially.

---

## 📌 Final Conclusion

The analysis indicates that customer satisfaction is associated with multiple factors rather than a single variable. Membership type, customer spending, purchase quantity, age, and shopping behavior all show meaningful relationships with satisfaction levels.

Overall, the project demonstrates how Exploratory Data Analysis can transform raw customer data into actionable business insights that can support data-driven decision-making.

---

## 👨‍💻 Author

**Harsh Gupta**

If you found this project helpful, consider giving the repository a ⭐.
