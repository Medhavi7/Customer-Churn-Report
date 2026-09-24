# Telco Customer Churn Analysis

An interactive Power BI report that analyzes customer churn across contract type, tenure, service adoption, payment method, and customer value. The report turns a public telecom dataset into retention-focused insights and recommended actions for at-risk customer segments.


## Business Objective

The goal of this project is to help a telecom provider answer four practical questions:

- How large is the current churn problem?
- Which customer segments have the highest churn exposure?
- What factors are most strongly associated with churn?
- Which retention actions should be prioritized?

## Dashboard Pages

### 1. Executive Account Overview

Summarizes the customer base, active and lost accounts, churn rate, monthly recurring revenue, revenue at risk, and churn patterns by contract and tenure.

### 2. Retention & Account Health

Segments customers by account risk, contract, technical support, online security, and tenure. It also highlights high-risk and high-value accounts for targeted retention outreach.

### 3. Churn Analysis

Uses Power BI's Key Influencers visual and supporting charts to examine the relationships between churn and contract type, online security, technical support, internet service, payment method, tenure, dependents, and service adoption.

### 4. Recommendations

Translates the analysis into retention priorities, including contract conversion, proactive outreach, stronger onboarding, service cross-selling, and pricing review.

## Key Findings

- The portfolio contains **7,043 customers**, of whom **1,869 churned**, producing an overall churn rate of approximately **26.5%**.
- Month-to-month customers have a **43% churn rate**, compared with **11%** for one-year contracts and **3%** for two-year contracts.
- Customers in their first 0-6 months have a **53% churn rate**, nearly twice the portfolio average.
- Month-to-month contracts are the strongest churn indicator in the Key Influencers analysis, increasing the likelihood of churn by **6.32x**.
- Customers without online security or technical support show materially higher churn exposure.
- Electronic-check customers are **2.65x** more likely to churn than customers using other payment methods.
- The dashboard identifies approximately **$67.37K in monthly revenue at risk** across high-risk active accounts.

## Recommended Actions

1. Encourage eligible month-to-month customers to move to longer-term contracts.
2. Prioritize proactive outreach to high-value, high-risk accounts.
3. Strengthen onboarding during the first six months of the customer relationship.
4. Cross-sell technical support and online security services where relevant.
5. Review pricing and value perception for high-charge, short-tenure customers.

## Tools and Techniques

- Power BI Desktop and Power BI Service
- Data modeling and DAX measures
- KPI design and customer-risk segmentation
- Interactive slicers, drillable tables, and cross-filtering
- Key Influencers analysis
- Business-focused dashboard storytelling

## Dataset

This project uses the **Telco Customer Churn** dataset published on Kaggle and originally provided as an IBM sample dataset.

- Source: [Telco Customer Churn on Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Records: 7,043 customers
- Features: 21 customer demographic, account, service, billing, and churn fields

The raw dataset is not redistributed in this repository. Download it directly from Kaggle using the link above.

## Repository Contents

```text
telco-customer-churn-analysis/
├── assets/
│   └── dashboard-overview.png
├── Telco-Customer-Churn-Dashboard.pbix
├── Telco-Customer-Churn-Dashboard.pdf
└── README.md
```

## How to View the Project

- Open `Telco-Customer-Churn-Dashboard.pdf` for a four-page static preview.
- View the screenshot above for the executive overview.
- Open `Telco-Customer-Churn-Dashboard.pbix` in Power BI Desktop to inspect the report file.

> **Note:** The PBIX file uses a live connection to a Power BI Service semantic model. The PDF and repository image provide the accessible public preview; opening the connected report may require permission to the original Power BI workspace.

## Disclaimer

This is a portfolio project created for educational and analytical purposes using a public dataset. The findings are specific to this sample and should not be interpreted as results from a real telecom company.
