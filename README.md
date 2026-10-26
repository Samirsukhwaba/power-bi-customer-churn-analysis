# Customer Churn Analysis Dashboard | Power BI

## Project Overview

This project uses Microsoft Power BI to analyse customer churn and identify patterns related to customer retention. An interactive dashboard helps explore customer demographics and factors associated with customers leaving a service.

## Objectives

- Calculate the overall customer churn rate.
- Analyse customer demographics.
- Investigate churn by contract type.
- Compare churn across payment methods and internet services.
- customer tenure distribution across monthly range.
- Present insights through interactive visualisations.

## Tools and Technologies

- **Power BI Desktop:** Dashboard development and visualisation.
- **Power Query:** Data cleaning and transformation.
- **DAX:** Measures and calculations.
- **Data Modelling:** Organising data for analysis.

## Dashboard Pages

1. **Churn Rate Overview:** Summarises customer numbers, churned customers and churn rate.
2. **Customer Demographics:** Explores customer characteristics and churn patterns.
3. **Customer Tenure Distribution:** Visualises the number of customers across monthly tenure ranges, from 0–11 months to 72–83 months.
4. **Churn Analysis:** Examines churn by contract type, payment method and internet service.

## Key Measures

- Total Customers
- Churned Customers
- Churn Rate

Example DAX measure:

```DAX
Churn Rate =
DIVIDE(
    [Churned Customers],
    [Total Customers],
    0
)
```

The measure calculates the percentage of customers who have churned. The final `0` returns zero if the total customer count is zero.

## Dataset

The project uses a single CSV file containing customer information and churn-related data.

## Key Findings

Add three to five findings based on the actual results shown in the dashboard, including relevant figures.

## Project Files

- **Power BI report:** `dashboard/Customer_Churn_Dashboard.pbix`
- **Dataset:** `data/customer_churn.csv`
- **Screenshots:** `screenshots/`

## What I Learned

This project strengthened my skills in data cleaning, DAX calculations, data modelling and dashboard development using Power BI. It also helped me practise analysing customer behaviour and presenting insights through interactive visualisations.
