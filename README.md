# NGO Programme Performance Analysis

## Overview

This project analyzes a synthetic NGO beneficiary and programme performance dataset using Microsoft Excel. The analysis focuses on data cleaning, beneficiary demographics, programme participation, assistance allocation, vulnerability, programme status, and programme outcomes.

## Objectives

- Clean and prepare beneficiary data for analysis
- Identify and address data quality issues such as duplicates, missing values, invalid ages, and negative assistance values
- Analyze beneficiary demographics and programme participation
- Evaluate assistance allocation across programmes
- Analyze programme and outcome performance
- Create a dashboard to communicate key findings and support data-driven decision-making

## Tools Used

- Microsoft Excel
- Excel Formulas
- Excel PivotTables
- Excel Charts
- GitHub

## Dataset

The cleaned dataset contains **1,000 unique beneficiary records** across **10 counties** and **5 programmes**.

Key fields include:

- Beneficiary ID
- Registration Date
- County
- Sub-County
- Programme
- Gender
- Age
- Household Size
- Vulnerability Category
- Assistance Type
- Assistance Value (KES)
- Programme Status
- Outcome Status
- Referral Status
- Enumerator ID
- Follow-Up Date
- Age Group

## Data Cleaning

The following data quality issues were identified and addressed:

- **12 duplicate records** were removed, leaving 1,000 unique records.
- Missing values were identified in Age, County, Assistance Value, and Outcome Status.
- Invalid ages below 18 and above 80 were identified and cleared.
- Five negative assistance values were corrected from **-KES 5,000 to KES 5,000**.
- Categorical fields such as Gender and Programme Status were checked for consistency.
- Final verification confirmed **1,000 records** in the cleaned dataset.

## Key Findings

- The programme dataset contains **1,000 beneficiaries across 10 counties**.
- **High vulnerability** was the largest vulnerability category, representing **33.4%** of beneficiaries.
- **Cash Assistance** had the highest number of beneficiaries, with **210 beneficiaries (21.0%)**.
- **Nairobi** had the highest number of beneficiaries at **116 (11.6%)**, while **Mombasa** had the lowest at **83 (8.3%)**.
- Total assistance provided was **KES 29,242,025**.
- **Education Support** received the highest total assistance at **KES 6,206,923**.
- Education Support also had the highest average assistance per beneficiary at **KES 31,994.45**.
- The recorded outcome achievement rate was **25.92%**.
- **255 beneficiaries** had outcomes marked as **Pending Assessment**, highlighting the need for further follow-up.

## Dashboard

The Excel dashboard presents key programme performance indicators and visualizations covering:

- Beneficiaries by Programme
- Beneficiaries by County
- Beneficiaries by Vulnerability Category
- Beneficiaries by Programme Status
- Beneficiaries by Outcome Status
- Beneficiaries by Assistance Type
- Beneficiaries by Gender

## Recommendations

- Prioritize follow-up for beneficiaries with pending outcome assessments.
- Strengthen data quality controls during data collection.
- Review assistance allocation across programmes to ensure resources are aligned with beneficiary needs and programme priorities.
- Improve county-level data completeness.
- Strengthen follow-up and support for high- and severe-vulnerability beneficiaries.
- Conduct regular data quality reviews to identify duplicates, missing values, and invalid records before analysis.

## Project Structure

```text
ngo-programme-performance-analysis/
├── NGO_Programme_Performance_Analysis.xlsx
├── data/
│   └── NGO_Programme_Performance_Raw_Data.xlsx
└── Screenshots/
    ├── dashboard-1.png
    ├── dashboard-2.png
    └── dashboard-3.png
```

## Project File

The complete Excel analysis workbook is available in this repository:

`NGO_Programme_Performance_Analysis.xlsx`
