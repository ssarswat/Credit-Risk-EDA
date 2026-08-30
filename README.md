# Credit Risk Analysis & Exploratory Data Analysis

## Project Overview

This project applies Exploratory Data Analysis (EDA) to loan application data to identify factors associated with loan default and generate insights relevant to credit-risk decision making.

The analysis examines applicant characteristics, financial attributes, loan characteristics and historical application behaviour to understand patterns associated with repayment and default.

## Objectives

- Identify variables and patterns associated with loan default.
- Analyse the characteristics of applicants who defaulted versus those who did not.
- Examine relationships between demographic, financial and loan-related variables.
- Analyse historical loan application information to identify additional risk-relevant patterns.
- Translate analytical findings into recommendations for credit-risk assessment.

## Dataset

The analysis uses two related datasets:

- Current loan application data: 307,511 records and 122 variables.
- Previous loan application data: 1,670,214 records and 37 variables.

The historical application data was subsequently integrated with the current application data to support a broader analysis of applicant and loan behaviour.

## Methodology

The analysis followed an end-to-end EDA workflow:

1. Data understanding and profiling
2. Missing-value analysis and imputation
3. Data cleaning
4. Outlier identification and assessment
5. Univariate analysis
6. Segmented univariate analysis
7. Bivariate analysis
8. Correlation analysis
9. Integration of historical application data
10. Identification of major risk-related patterns
11. Development of analytical recommendations

## Key Areas of Analysis

The analysis examined relationships involving:

- Applicant income
- Credit and loan amounts
- Age
- Employment characteristics
- Family and household characteristics
- Education
- Housing and asset ownership
- Contact and address information
- Previous loan applications
- Loan purposes
- Insurance behaviour

## Key Insights

The analysis identified several patterns associated with observed default behaviour, including:

- Default rates varied across income ranges.
- Default behaviour showed relationships with loan/credit amount.
- Applicant age and family characteristics showed observable differences between default and non-default groups.
- Asset ownership characteristics showed differences in observed default rates.
- Contact and address-related information exhibited associations with default behaviour.
- Historical application data provided additional context for understanding applicant and loan behaviour.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Exploratory Data Analysis
- Data Cleaning
- Data Visualization
- Statistical Analysis

## Repository Contents

- `Credit_Risk_EDA.ipynb` — complete exploratory data analysis notebook.

## Limitations

This project focuses on exploratory analysis and identification of associations in the data. It does not develop or validate a production credit-default prediction model.

Observed relationships should therefore be interpreted as analytical associations rather than causal relationships.

## Author

**Sushant Sarswat**

MS, Data Science
