# BankSight-Analytics
BankSight Analytics is an end-to-end data analytics solution developed to uncover financial insights and support strategic decision-making in the banking domain. 
# 1. Problem Statement
Financial institutions generate massive volumes of customer-related data, yet lack effective mechanisms to interpret this data for strategic decision-making. Without structured analysis and visual dashboards, it becomes difficult to identify patterns in loans, deposits, income segments, and customer behavior.
This project aims to build a complete end-to-end banking dashboard solution, leveraging Python for Exploratory Data Analysis (EDA) and Power BI for interactive visual reporting, to support data-driven business insights.

# 2. Project Objectives
To perform EDA using Python to uncover hidden trends and clean the dataset.

To visualize banking metrics such as total loans, deposits, credit balances, account types, and estimated income.

To segment data by nationality, gender, occupation, income band, and banking relationships.

To design a summary dashboard for easy executive reporting.

# 3. Dataset Overview
Key fields analyzed and visualized:

  Demographic Data:  Client ID, Name, Age, GenderId, Nationality, Occupation

  Financial Data: Fee Structure, Estimated Income, Superannuation Savings, Credit Card Balance, Bank Loans, Bank Deposits, Checking Accounts, Saving Accounts, Foreign Currency Account, Business Lending

  Classification & Metadata: Loyalty Classification, Risk Weighting, BRId, IAId

# 4. Tools & Technologies Used
   Python (Pandas, Matplotlib, Seaborn): For data preprocessing and exploratory data analysis (EDA)

  Power BI: For data modeling and visualization

  Excel/CSV: As the original data source for transformation and loading

# 5. Methodology
### Data Preparation in Python:

  Cleaned missing and inconsistent values using pandas

  Generated summary statistics, distribution plots, and correlation heatmaps

  Identified outliers and anomalies in numeric fields like Credit Card Balance and Loan Amount

### Data Modeling in Power BI:

Built relationships between fact and dimension tables

Categorized clients by banking relationship, income band, and nationality

### Dashboard Design:

Created pages: Loan Analysis, Deposit Analysis, Summary

Added interactive filters (gender, year, banking relationship)

Used KPI cards, bar charts, and donut charts for key metrics

# 6. Key Findings
Loan Distribution: Private Banks have the highest share of bank loans (0.81bn).

Occupation Insight: 'Web Developer I' has the highest loan volume.

Income Band Analysis: Clients in the High-Income Band contribute over 50% to bank loans and deposits.

Deposit Pattern: Checking Accounts hold more value than Savings Accounts.

Geographic Insight: European and Asian clients show higher engagement across banking products.

# 7. Conclusion
Combining Python and Power BI provided a comprehensive approach to analyzing and visualizing banking data. While Python enabled deep EDA and data cleaning, Power BI facilitated effective dashboard reporting for business stakeholders.

# 8. Future Enhancements
Include predictive analytics (e.g., loan default prediction) using Python machine learning models.

Add dynamic drill-through features in Power BI for client-level analysis.

Automate data refresh from databases instead of static Excel files.
