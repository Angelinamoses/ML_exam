Problem Statement

Hospitals rely heavily on critical equipment such as ventilators, MRI machines, and monitoring devices. However, there is often a lack of proactive monitoring systems to identify early signs of equipment stress or failure. This leads to unexpected breakdowns, inefficient maintenance scheduling, and potential risks to patient care.

The challenge is to analyze equipment usage, maintenance patterns, and environmental factors to identify hidden risks and inefficiencies before failures occur.

Observations
Equipment with high usage hours shows a clear increase in risk levels, indicating overutilization impacts performance.
Long gaps between maintenance activities significantly contribute to higher failure risk, highlighting poor maintenance scheduling.
Elevated temperature conditions are associated with increased equipment risk, suggesting environmental influence on performance.
Certain equipment types consistently fall into higher risk categories, indicating uneven workload distribution.
A small subset of equipment contributes to a majority of high-risk cases, meaning targeted monitoring can reduce system failures effectively.

Solution Approach

To address these challenges, a rule-based analytical system was developed:

Created a synthetic dataset simulating hospital equipment behavior
Performed Exploratory Data Analysis (EDA) to identify patterns
Engineered a risk scoring system based on:
Usage intensity
Maintenance delay
Temperature conditions
Categorized equipment into:
Low Risk
Medium Risk
High Risk

Summary

This project demonstrates how data-driven analysis can be used to uncover hidden risks in hospital equipment management. By combining EDA, feature engineering, and rule-based logic, the system provides actionable insights without relying on complex machine learning models.

The dashboard enables be
