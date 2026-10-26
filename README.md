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
  
   <img width="1189" height="671" alt="Screenshot 2026-10-26 at 3 43 33 pm" src="https://github.com/user-attachments/assets/aca1f6e0-43ae-4e71-9e82-c5180bb52f76" />

   
3. **Customer Demographics:** Explores customer characteristics and churn patterns.
   
   <img width="1189" height="671" alt="Screenshot 2026-10-26 at 3 43 42 pm" src="https://github.com/user-attachments/assets/560c7850-e5e2-4ce4-a279-957700825703" />

   
5. **Customer Tenure Distribution:** Visualises the number of customers across monthly tenure ranges, from 0–11 months to 72–83 months.
   
     <img width="1189" height="671" alt="Screenshot 2026-10-26 at 3 43 56 pm" src="https://github.com/user-attachments/assets/a140d732-3b78-477d-8d71-149105566a20" />
7. **Churn Analysis:** Examines churn by contract type, payment method and internet service.
   
   <img width="1189" height="671" alt="Screenshot 2026-10-26 at 3 43 50 pm" src="https://github.com/user-attachments/assets/045870a8-166c-4215-b287-59e4a3371d9f" />


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



## What I Learned

This project strengthened my skills in data cleaning, DAX calculations, data modelling and dashboard development using Power BI. It also helped me practise analysing customer behaviour and presenting insights through interactive visualisations.
