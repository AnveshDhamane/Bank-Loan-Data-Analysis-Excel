# Bank Loan Analytics Dashboard

## Project Overview

This dashboard is designed to analyze the lending operations of a financial institution. It assesses the health of the loan portfolio, identifies trends in borrower demographics, tracks repayment performance, and highlights potential risks.

The project demonstrates skills in:
- Excel Data Cleaning & Processing
- Advanced PivotTables & Data Modeling
- KPI Calculation & Risk Assessment
- Interactive Dashboard Design
- Demographic & Financial Analysis

## Dataset Description

The dataset contains comprehensive loan records, including borrower details, loan terms, and repayment status. Below is the data dictionary explaining key columns.

### Data Dictionary

| Column Name | Description |
|-------------|-------------|
| **Account ID** | Unique identifier for each loan account. |
| **Loan Amount** | The amount applied for by the borrower. |
| **Funded Amount** | The actual amount disbursed by the bank. |
| **Loan Status** | Current status of the loan (Current, Fully Paid, Charged Off, etc.). |
| **Grade / Sub Grade** | Risk classification assigned to the loan (A1, B2, etc.). |
| **Interest Rate** | Annual interest rate applicable to the loan. |
| **Term** | Duration of the loan (e.g., 36 months, 60 months). |
| **Purpose** | Reason for the loan (Debt consolidation, Business, Medical, etc.). |
| **Home Ownership** | Borrower's housing status (Rent, Own, Mortgage). |
| **Annual Income** | Annual income of the borrower. |
| **Issue Date** | The date the loan was funded. |
| **State / Region** | Geographic location of the borrower. |
| **Delinquency Status** | Indicators for past due payments (Is Delinquent Loan: Y/N). |

## Dashboard Preview

![Bank Loan Dashboard Screenshot](https://github.com/AnveshDhamane/Bank-Loan-Data-Analysis-Excel/blob/f3a8b50b32bbac5ead2e420254f2ebad5ea2ce3b/Bank%20Loan%20Dashboard.png)

## Features

### 1. Key KPIs
- **Total Funded Amount**: The total principal amount disbursed to borrowers.
- **Total Interest Earned**: Revenue generated from loan interest.
- **Total Collections**: Aggregate amount collected (Principal + Interest).
- **Delinquency Rate**: Percentage of loans that are past due.
- **Average Interest Rate**: The weighted average rate across the portfolio.

### 2. Visual Insights
- **Loan Status Distribution**: Breakdown of Active, Fully Paid, and Non-Performing Assets (NPA).
- **Demographic Analysis**: Loan distribution by Gender, Age Group, and Religion.
- **Geographic Trends**: State and Region-wise lending performance.
- **Purpose-wise Funding**: Analysis of loans for Business, Agriculture, and other categories.
- **Time-Series Trends**: Yearly and monthly disbursement trends.

### 3. Interactive Filters
- **Year / Quarter**: Filter data by disbursement timeline (e.g., 2017-2020).
- **Region / State**: Drill down into specific geographic markets.
- **Loan Grade**: Filter by risk grade (A, B, C, etc.).
- **Purpose Category**: Filter by loan usage (Agriculture, Business, Personal).

## Tools Used

- **Microsoft Excel**: Primary tool for data storage and manipulation.
- **PivotTables**: Used for aggregating loan data by various dimensions.
- **PivotCharts**: Visual representation of trends and distributions.
- **Slicers**: To enable interactive filtering on the dashboard.
- **Data Cleaning**: Handling missing values and standardizing formats (Date, Currency).

## Key Insights

### 1. High Portfolio Health
The portfolio demonstrates exceptional performance with a **Delinquency Rate of only ~1.56%**, indicating strict underwriting standards and high borrower quality.

### 2. Significant Gender Disparity in Lending
The data reveals a massive focus on female borrowers (**~$750M** funded) compared to male borrowers (**~$273K**). This suggests a business model heavily skewed towards women-centric financing or micro-finance groups.

### 3. Strong Repayment Behavior
The majority of loans are either **"Active" (~$401M)** or **"Fully Paid" (~$187M)**. Non-Performing Assets (NPA) constitute a very small fraction (~$5.8M) relative to the total volume.

### 4. Youth & Middle-Age Dominance
Borrowing is most prevalent among the **26-35** and **36-45** age groups, which combined account for over **$500M** of the loan book.

### 5. Business & Agriculture Lead Funding
The primary drivers for borrowing are **Business** loans (~$80M) and **Agriculture** loans (~$36M), highlighting the productive nature of the deployed capital.

## Recommendations

### 1. Sustain Female-Centric Products
Given the success and volume of female borrowers, the bank should continue to tailor products (e.g., lower rates, flexible terms) specifically for women entrepreneurs to maintain this stronghold.

### 2. Monitor "Active" Loan Transition
With ~$401M in Active loans, implementing early warning systems for the 26-35 age demographic could prevent future delinquencies as this group holds the largest share of debt.

### 3. Diversify Male Borrower Base
There is a largely untapped market among male borrowers. Creating targeted marketing campaigns for men in the 26-45 age bracket could diversify the portfolio risk.

### 4. Expand High-Performing Regions
Regions with high activity should be analyzed for further expansion. Branch presence or digital marketing in neighboring high-potential districts could boost revenue.

### 5. Cross-Sell to "Fully Paid" Customers
Customers with "Fully Paid" status ($187M volume) represent low-risk opportunities. They should be targeted for premium loan products or higher-ticket business loans.

### 6. Review "Write-Off" Patterns
Although low, analyzing the specific attributes (Grade, Purpose) of the loans that went to "Write Off" can help refine future credit scoring models.
