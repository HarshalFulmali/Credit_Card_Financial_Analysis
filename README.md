# Credit Card Financial Analysis Dashboard – 2023

## Project Overview

This project focuses on analyzing credit card transactions and customer data for the year 2023 using **Microsoft Power BI**.

The objective of this project is to analyze credit card revenue, transaction patterns, customer demographics, card categories, expenditure types, and customer behavior to identify meaningful business insights.

The analysis is performed using two datasets:
1. **Credit Card Details:** Contains information about credit card transactions, revenue, interest earned, card categories, expenditure types, and transaction methods.
2. **Customer Details:** Contains customer demographic information such as gender, education, job, marital status, age group, state, and dependent count.

Two interactive Power BI dashboards have been developed to provide a comprehensive overview of credit card performance and customer behavior.

---

## Project Objectives

- Analyze overall credit card revenue and transaction performance.
- Identify the highest-performing quarters and card categories.
- Understand customer spending patterns across different expenditure types.
- Analyze revenue based on customer education and occupation.
- Evaluate customer demographics and their contribution to revenue.
- Identify delinquent accounts and their distribution across customer segments.
- Understand revenue contribution by gender, age group, marital status, and geographical location.

---

## Dashboard Overview

### 1. Credit Card Transaction Report

This dashboard provides an overview of credit card transaction performance, revenue generation, interest earned, and customer spending patterns.

### Key Performance Indicators (KPIs)

| KPI | Value |
|---|---:|
| Total Revenue | $55.3M |
| Interest Earned | $7.8M |
| Total Transaction Amount | $44.5M |
| Total Transactions | 655,651 |

### Key Insights

**1. Quarterly Revenue and Transaction Analysis**
- Q3 generated the highest revenue of approximately **$14.2M** and recorded the highest transaction count of approximately **166K**.
- Q1 secured the second position in revenue generation with approximately **$14.0M**, but ranked third in transaction count with approximately **163.3K**.
- Q3 was the strongest-performing quarter in terms of both revenue and transaction volume.

**2. Revenue Analysis by Card Category**
- Blue Card generated the highest revenue of approximately **$46.14M**, with a transaction amount of approximately **$36.96M** and interest earned of approximately **$6.50M**.
- Silver Card secured the second position across the major performance metrics.
- Blue Card contributes the largest share of overall credit card revenue.

**3. Revenue by Transaction Method**
- Swipe transactions generated the highest revenue of approximately **$35M**.
- Chip transactions contributed approximately **$17M**.
- Online transactions generated approximately **$3M**.
- Swipe transactions are the leading transaction method in terms of revenue generation.

**4. Revenue by Expenditure Type**

| Expenditure Type | Approximate Revenue |
|---|---:|
| Bills | $14M |
| Entertainment | $10M |
| Fuel | $9M |
| Grocery | $9M |
| Food | $8M |
| Travel | $6M |

- Bills accounted for the highest revenue contribution, followed by Entertainment.
- Fuel and Grocery generated almost equal revenue.
- Travel contributed the lowest revenue among the expenditure categories.

**5. Revenue by Customer Education Level**
- Graduates generated the highest revenue of approximately **$22M**.
- High School customers contributed approximately **$11M**.
- Unknown and Uneducated customer segments each generated approximately **$8M**.
- Post-Graduate customers contributed a comparatively lower revenue.

**6. Revenue by Customer Occupation**
- Businessmen generated the highest revenue of approximately **$17M**.
- White Collar customers contributed approximately **$10M**.
- Self-Employed and Government Employees each generated approximately **$8M**.
- Blue Collar customers contributed approximately **$7M**.
- Retirees generated the lowest revenue of approximately **$5M**.

---

### 2. Credit Card Customer Report

This dashboard focuses on customer demographics, customer satisfaction, delinquent accounts, and revenue contribution across different customer segments.

### Key Performance Indicators (KPIs)

| KPI | Value |
|---|---:|
| Total Customers | 10,108 |
| Female Customers | 5,880 |
| Male Customers | 4,228 |
| Delinquent Accounts | 614 |
| Average Customer Rating | 3.2 |

### Key Insights

**1. Customer Distribution and Delinquent Accounts**
- The dataset contains a total of **10,108 customers**.
- Female customers account for 5,880, while male customers account for 4,228.
- A total of **614 accounts are identified as delinquent accounts**.
- Female customers represent the larger share of the customer base.

**2. Delinquent Accounts by Education Level**
- Graduates account for the highest number of delinquent accounts, with **238 accounts**.
- High School customers account for 108 delinquent accounts.
- Customers with an unknown education level also account for 108 delinquent accounts.
- Graduate customers represent the largest segment of delinquent accounts.

**3. Weekly Revenue Analysis by Gender**
- Male customers generally contributed more revenue than female customers throughout most weeks of the year.
- In Q1, during the 12th week (March 12), female customers generated revenue of approximately **$639.6K**, exceeding male customers' revenue of approximately **$491.7K**.
- The highest weekly revenue contributions by gender across the quarters were:

| Quarter | Highest Revenue | Gender |
|---|---:|---|
| Q1 | $715,281.7 | Male |
| Q2 | $771,655.4 | Male |
| Q3 | $691,886.7 | Male |
| Q4 | $612,569.1 | Male |

- Male customers dominated revenue contribution across all four quarters.

**4. Revenue Analysis by State and Gender**

The top five states based on revenue generation are:

| State | Female Revenue | Male Revenue |
|---|---:|---:|
| Texas | $6M | $7M |
| New York | $6M | $7M |
| California | $7M | $6M |
| Florida | $4M | $6M |
| New Jersey | $1M | $3M |

- Texas and New York recorded the highest combined revenue contributions among the listed states.
- In California, female customers contributed more revenue than male customers.
- Male customers generated higher revenue in Florida and New Jersey.

**5. Revenue by Marital Status and Gender**
- Married male customers generated the highest revenue of approximately **$15M**.
- Married female customers contributed approximately **$13M**.
- Single male customers generated approximately **$12M**.
- Single female customers contributed approximately **$11M**.
- Customers with unknown marital status contributed the remaining revenue.

**6. Revenue by Age Group and Gender**
- Customers aged **40–49 years** generated the highest revenue among all age groups.
  - Female customers contributed approximately $11M.
  - Male customers contributed approximately $14M.
- Customers aged **50–59 years** secured the second position.
  - Female customers contributed approximately $9M.
  - Male customers contributed approximately $10M.
- The 40–49 age group represents the strongest revenue-generating customer segment.

**7. Customer Dependents Analysis**
- Most customers have approximately **2–3 dependents**.
- This provides an overview of the family responsibilities and demographic composition of the customer base.

---

## Tools & Technologies Used

- **Microsoft Power BI:** Dashboard development and data visualization.
- **Power Query:** Data cleaning and transformation.
- **DAX:** Calculated measures and KPI development.
- **Data Modeling:** Relationship management between customer and transaction datasets.
- **Data Visualization:** Charts, tables, KPIs, and interactive reports.

---

## Key Business Findings

Based on the analysis, the following major findings were identified:

1. **Strong Quarterly Performance:** Q3 generated the highest revenue and transaction volume.
2. **Leading Card Category:** Blue Card contributed the largest share of total revenue.
3. **Preferred Transaction Method:** Swipe transactions generated significantly more revenue than Chip and Online transactions.
4. **Major Expenditure Category:** Bills accounted for the highest expenditure-related revenue.
5. **High-Value Customer Segments:** Graduates and Businessmen were the leading revenue-generating customer segments.
6. **Gender-Based Revenue:** Male customers generally contributed more revenue than female customers.
7. **Geographical Performance:** Texas and New York were among the highest revenue-generating states.
8. **Important Age Segment:** Customers aged 40–49 contributed the highest revenue.
9. **Delinquency Monitoring:** A total of 614 customer(6.07%) accounts were identified as delinquent, making this an important area for further investigation.

---

## Conclusion

This Credit Card Financial Analysis project provides valuable insights into credit card transaction performance and customer behavior during 2023.

The analysis highlights the importance of understanding revenue trends, transaction methods, card categories, customer demographics, and delinquent accounts.

The two Power BI dashboards help transform raw customer and transaction data into meaningful business insights that can support data-driven decision-making.

---

## Author

**Harshil Fulmali**

Data Analysis | Python | Power BI

