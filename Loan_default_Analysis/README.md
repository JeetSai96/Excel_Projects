# Loan Default Analysis Dashboard — Excel

## Project Overview

This project focuses on analyzing loan default patterns using Microsoft Excel. The objective is to explore borrower characteristics, loan attributes and financial indicators to understand how default rates vary across different categories.

The project uses Excel data cleaning, calculated columns, PivotTables, PivotCharts and interactive slicers to create a dynamic dashboard for loan portfolio analysis.

## Dashboard Preview
*The dashboard provides an interactive overview of loan performance and default patterns.*
<img width="1821" height="692" alt="image" src="https://github.com/user-attachments/assets/1b4002f1-c819-466b-9a13-7042b8de633e" />


## Business Objectives

- Analyze total, defaulted and non-defaulted loans.
- Calculate the overall loan default rate.
- Examine default rates across age groups and employment types.
- Compare default patterns by credit score, income, interest rate and loan amount.
- Explore the relationship between default rates and debt-to-income (DTI) groups.
- Compare default rates by loan purpose, mortgage status and co-signer status.

## Tools and Techniques

- **Microsoft Excel**
- Excel Tables and structured references
- Data cleaning and transformation
- Calculated columns and formula-based categorization
- Data validation and conditional formatting
- PivotTables and PivotCharts
- Interactive slicers
- KPI cards and dashboard design

## Dataset

The dataset contains loan-level information covering borrower demographics, financial characteristics, loan details and default status.

Key fields include:

- Age and Income
- Loan Amount and Loan Term
- Credit Score and Interest Rate
- Months Employed and Number of Credit Lines
- Debt-to-Income (DTI) Ratio
- Education, Employment Type, and Marital Status
- Mortgage, Dependents, and Co-signer status
- Loan Purpose and Default status

**Default coding:** `1` represents a defaulted loan and `0` represents a non-defaulted loan.

*Note: Refer to the dataset's original source for its provenance, collection methodology and any usage restrictions.*

## Data Preparation

The dataset was prepared for analysis through cleaning and transformation steps. Additional calculated columns were created to group continuous variables into categories, including:

- Age Group
- Income Group
- Credit Score Group
- Loan Amount Group
- Interest Rate Group
- Employment Duration Group
- DTI Group
- Default Status

These categories support comparisons across borrower segments and loan characteristics.

## Dashboard KPIs

The dashboard includes five key performance indicators:

1. **Total Loans** — Total number of loan records.
2. **Defaulted Loans** — Number of loans marked as defaulted.
3. **Non-Defaulted Loans** — Number of loans marked as non-defaulted.
4. **Default Rate** — Proportion of loans marked as defaulted.
5. **Average Loan Amount** — Average loan amount across the selected records.

## Analysis and Visualizations

The dashboard uses PivotCharts to compare loan counts and default rates across:

- Age Group
- Employment Type
- Credit Score Group
- Loan Purpose
- Income Group
- Interest Rate Group
- DTI Group
- Loan Amount Group

Interactive slicers allow users to filter the dashboard by age group, employment type, loan purpose, mortgage status and co-signer status.

## Key Insights

The dashboard is designed to help users identify categories with comparatively higher or lower default rates and explore how loan performance changes under different filter selections.

## How to Use

1. Download or clone this repository.
2. Open the Excel workbook in Microsoft Excel.
3. Navigate to the dashboard worksheet.
4. Use the slicers to filter the loan portfolio.
5. Review the KPI cards and charts to compare loan counts and default rates.
6. Refresh the PivotTables when the underlying dataset changes.

## Project Structure

```text
Loan-Default-Analysis/
├── README.md
├── Loan_Default_Analysis.xlsx
```

## Conclusion

This project demonstrates the use of Excel for data preparation, categorical analysis, KPI reporting and interactive dashboard development. It provides a practical example of transforming raw loan data into a structured analytical tool for exploring loan default patterns.

