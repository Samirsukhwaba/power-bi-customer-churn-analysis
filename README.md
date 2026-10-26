Customer Churn Analysis Dashboard | Power BI

Project Overview

This project uses Microsoft Power BI to analyse customer churn and identify patterns associated with customer retention.

The dashboard transforms customer data into interactive visualisations to help users understand customer churn rates and explore the factors associated with customers leaving a service.

Objectives

* Calculate and monitor the overall customer churn rate.
* Analyse customer demographics.
* Investigate churn patterns across different contract types.
* Examine churn across payment methods.
* Compare churn across internet service categories.
* Present findings through an interactive dashboard.

Tools and Technologies

* Power BI Desktop: Dashboard development and data visualisation.
* Power Query: Data cleaning and transformation.
* DAX: Measures and calculations.
* Data modelling: Organising data for analysis.

Dashboard Pages

1. Churn Rate Overview

Provides a high-level overview of customer churn and retention.

2. Customer Demographics

Explores customer characteristics and their relationship with churn.

3. Churn Analysis

Examines churn patterns across contract types, payment methods and internet services.

Key Measures

* Total Customers
* Churned Customers
* Churn Rate

Example DAX measure:

Churn Rate =
DIVIDE(
    [Churned Customers],
    [Total Customers],
    0
)

The measure divides the number of churned customers by the total number of customers. The third argument returns zero if the denominator is zero.

Key Findings

Add three to five findings based on the actual results shown in your dashboard.

For example, identify which contract type has the highest churn rate, if your analysis supports that conclusion. Include actual figures from your report rather than assumptions.

Project Files

* Power BI report: dashboard/Customer_Churn_Dashboard.pbix
* Dashboard screenshots: screenshots/
* Dataset information: data/README.md

What I Learned

This project helped me practise data cleaning, DAX calculations, data modelling and dashboard design using Power BI.

It also strengthened my ability to explore customer behaviour and communicate analytical findings through interactive visualisations.
