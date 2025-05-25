# HR-Analytics-Dashboard

## Overview  
This Power BI project features an **HR Analytics Dashboard** created to explore employee data and attrition trends. It visualizes key workforce metrics such as total headcount, attrition rate, salary distribution, and satisfaction levels to help HR teams uncover patterns and make informed decisions.

## Features  
- **KPI Cards**: Summarized metrics including Total Employees, Attrition Count, Attrition Rate, Average Age, Average Salary, and Average Tenure.  
- **Attrition Analysis**: Charts showing employee attrition by Salary Slab, Education Field, Age Group, Gender, and Years at Company.  
- **Job Role Comparison**: Insights into Job Satisfaction and Compensation by Job Role.  
- **Category Distributions**: Donut charts illustrating the spread of employees by Age Group, Gender, and Work-Life Balance.  
- **Interactive Slicers**: Filters for Department, Business Travel, Marital Status, and OverTime for dynamic, interactive reporting.  
- **Clean Layout**: Sections are clearly separated with titles and contextual headers for a professional look.

## Data Model Summary  

The data model is based on a single table named `HR_Analytics`. Below is a summary of its fields:

| **Category**         | **Fields**                                                                 |
|----------------------|----------------------------------------------------------------------------|
| Demographics         | Age, AgeGroup, Gender, MaritalStatus                                       |
| Employment Details   | Department, JobRole, YearsAtCompany, BusinessTravel, OverTime              |
| Compensation         | HourlyRate, MonthlyRate, SalarySlab                                        |
| Performance Metrics  | Attrition, JobSatisfaction, WorkLifeBalance                                |

Key calculated measures (using DAX):

- Total Employee Count  
- Attrition Count  
- Attrition Rate  
- Average Age  
- Average Salary  
- Average Years at Company  

The model is flat and designed for simplicity and clarity.

## Visualizations  
- **Cards**: High-level KPIs at the top of the report  
- **Bar Charts**: Attrition by Education Field, Salary Slab, Age Group, and Gender  
- **Clustered Columns**: Monthly Salary and Job Satisfaction by Job Role  
- **Donut Charts**: Gender, Age Group, and Work-Life Balance Distributions  
- **Interactive Slicers**: Allow filtering across charts by key attributes

## Insights  
- **Attrition Patterns**: Understand which segments (e.g., young professionals, certain education fields) show higher attrition.  
- **Compensation Trends**: Compare salaries across roles and see if low-paid positions align with high attrition.  
- **Work-Life Imbalance**: Discover correlations between poor Work-Life Balance and employee departures.  
- **Gender & Tenure Insights**: Examine if specific genders or experience levels are more likely to leave.  
- **Slicer-Driven Analysis**: Enables deeper analysis through filters (e.g., Marital Status + OverTime impact).

## Acknowledgments  
- **Dataset**: Based on common HR datasets available in public domain or synthetic data inspired by Kaggle HR analytics projects.  
- **Tool**: Created using Microsoft Power BI Desktop.  
- **Design**: Inspired by best practices in HR reporting and workforce dashboards.
