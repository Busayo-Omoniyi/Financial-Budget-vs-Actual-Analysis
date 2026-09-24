# Financial-Budget-vs-Actual-Analysis
<img width="907" height="509" alt="Executive" src="https://github.com/user-attachments/assets/f47201f1-d323-4cfe-9076-ea5e545b7cdc" />


## Project Overview

Management needs visibility into how effectively the company is managing its allocated budget and where unfavorable spending patterns are occurring.
This project analyzes three years of financial transaction data to compare budgeted amounts against actual spending and identify the departments, expense categories, periods and regions contributing to budget overruns.
Objective
Transform raw sales data into meaningful business insights through data cleaning, SQL analysis, interactive dashboards, and data storytelling.

## Reporting Period

January 2021 – December 2023

## Records Analyzed

10,000

## Tools

* MySQL
* Microsoft Power BI
* Microsoft Excel

## Business Qestions

1. Are we spending within budget, and how is budget performance changing over time?
2. Which departments are overspending or underspending the most?
3. Which expense categories are contributing most to overspending?
4. Which regions have the best and worst budget performance?
5. What actions should management take to improve budget performance?

## Data Preparaion & Quality Assessment

The original dataset contained 10,010 records and 8 columns covering transactions from January 2021 to December 2023.
Initial data quality checks identified:
10 exact duplicate records
8 missing values
Missing values across Region, Transaction ID, Category and Department

## Cleaning Approach

Using SQL, exact duplicate records were removed and missing categorical values were standardized as "Unknown" rather than being arbitrarily assigned to a business category.
The cleaned dataset contained 10,000 records and was then used for analysis and Power BI reporting.

## Analytical Approach

The analysis followed an end-to-end workflow:
Raw Data → SQL Data Quality Assessment → Cleaning → Business Questions → SQL Analysis → Validation → Power BI Modeling → Dashboard → Insights → Recommendations

Budget variance was calculated as: Actual Spending − Budget
Therefore, Positive variance = Overspending
                Negative variance = Spending below budget
This convention was used consistently throughout the analysis.

**(Key findings in Case study)**

### Executive Dashboard

Provides an overview of business performance through key KPIs, Actual spending vs budget trends, time & regional performance, and Department-category expense analysis.

<img width="907" height="509" alt="Executive" src="https://github.com/user-attachments/assets/69b5b6fe-78e4-4bd1-abbb-63c56d1df9e6" />

### Time & Performance Dashboard
<img width="909" height="511" alt="Time   perf" src="https://github.com/user-attachments/assets/8c0be7e8-6ce7-4247-b468-eb80a5f91a70" />

### Department & Expense drivers
<img width="914" height="515" alt="Dept   Expense" src="https://github.com/user-attachments/assets/9f3fc7f1-373c-4bb4-a98e-8f9f056210d4" />

### Regional Performance
<img width="913" height="513" alt="Regional perf" src="https://github.com/user-attachments/assets/e5254df3-5464-4afe-9a9d-a8d569c82610" />

### Glossary
<img width="911" height="513" alt="Glossary" src="https://github.com/user-attachments/assets/133502cf-8daa-4022-bb22-a38617e4bd80" />

## Contact

**Busayo Omoniyi Rebecca**

Email: hi.busayoniyi@gmail.com

LinkedIn: linkedin.com/in/busayo-omoniyi

Behance: behance.net/busayo-omoniyi
