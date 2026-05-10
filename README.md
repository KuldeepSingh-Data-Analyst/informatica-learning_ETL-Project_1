# Informatica Customer Churn Data Integration Project

## Overview
This repository contains a complete Informatica ETL project developed using customer churn datasets.  
The project demonstrates data extraction, transformation, filtering, aggregation, ranking, and reporting operations using Informatica PowerCenter concepts.

The project uses the following datasets:

- `Churn_Modelling2.csv`
- `Churn_Modelling3.csv`

The workflows and mappings are designed to perform real-world banking customer analytics and generate meaningful output reports.

---

# Objectives

The project performs the following tasks:

## 1. Total Balance Analysis
Calculate the total account balance for:

- Male customers
- Female customers

### Output:
Generated output file containing gender-wise balance totals.

---

## 2. Active Customer Count
Find the number of active customers based on gender:

- Active Male Customers
- Active Female Customers

### Output:
Generated output file containing active customer statistics.

---

## 3. Age Group Distribution
Create customer groups based on age ranges:

| Age Group | Range |
|-----------|-------|
| Young Customers | 18 – 30 |
| Middle Age Customers | 30 – 45 |
| Senior Customers | Above 45 |

### Output:
Distribution tables for each customer age category.

---

## 4. Available Balance Ranking
Filter customers having:

- `Balance > 0`

Then rank them in ascending order based on balance amount.

### Output:
Ranked customer dataset.

---

## 5. Top 5 Customers by Balance
Retrieve complete customer information for the top 5 highest balances.

### Output:
Output file containing complete records of top balance holders.

---

## 6. Credit Score Analysis
Find:

- Highest Credit Score
- Lowest Credit Score

### Output:
Summary output file containing minimum and maximum credit score values.

---

# Technologies Used

- Informatica PowerCenter
- ETL Workflows
- Source Qualifier
- Aggregator Transformation
- Rank Transformation
- Filter Transformation
- Expression Transformation
- CSV Data Sources

---

# Project Structure

```bash
├── datasets/
│   ├── Churn_Modelling2.csv
│   └── Churn_Modelling3.csv
│
├── mappings/
├── workflows/
├── output/
├── screenshots/
└── README.md
