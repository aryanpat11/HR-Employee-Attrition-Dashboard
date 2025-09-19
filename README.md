📊 HR Employee Attrition Dashboard
This repository contains my HR Employee Attrition project where I analyzed a sample employee dataset using Microsoft Power BI. The goal was to build an interactive dashboard to uncover key factors driving employee attrition, enabling data-driven decision-making for HR departments.

📂 Project Overview
Domain: HR Analytics / People Analytics

Tool Used: Microsoft Power BI

Dataset: HR Employee Attrition Sample (.xlsx format)

Output: Interactive Power BI Report (.pbix file)

🔧 Project Workflow
1. Data Cleaning & Transformation (in Power Query)
Corrected data types for columns like Age, MonthlyIncome, etc.

Removed duplicates to ensure data integrity.

Trimmed and cleaned text columns (Department, JobRole).

Created a calculated AttritionFlag (1 for "Yes", 0 for "No") to simplify calculations.

Added custom columns for AnnualIncome and AgeGroup to enable deeper analysis.

2. Data Modeling & DAX Measures
Developed key DAX measures to power the dashboard visuals:

Total Employees = COUNTROWS('Employees')

Attrition Count = SUM('Employees'[AttritionFlag])

Attrition Rate = DIVIDE([Attrition Count], [Total Employees])

Avg Monthly Income = AVERAGE('Employees'[MonthlyIncome])

3. Visualization & Dashboard Design
Designed a summary "Overview" page to display high-level insights at a glance.

Created KPI Cards for key metrics: Total Employees, Attrition Rate, Avg Monthly Income, and Avg Annual Income.

Developed multiple charts to break down attrition by different dimensions:

Bar Charts: Attrition by Department and Job Role.

Donut Chart: Attrition by Gender.

Column Chart: Attrition by Age Group.

Implemented interactive Slicers (Department, JobRole, Gender) and a Drillthrough feature to a detailed employee view.

💡 Key Insights
The company has a high attrition rate of 47%, indicating a significant challenge to retention.

The Manager job role experiences the highest number of departures, suggesting potential issues in leadership roles or career progression.

Attrition is most prevalent among employees in the 31-40 age group, a critical phase for career building.

The Marketing department has the highest number of employees leaving the company.

📸 Dashboard Snapshots
(Add a screenshot of your main dashboard 'Overview' page here.)

🛠️ Tools & Technologies
Power BI Desktop: Data visualization, modeling, and dashboard creation.

Power Query: For ETL (Extract, Transform, Load) processes.

DAX (Data Analysis Expressions): For creating custom calculations and measures.

Excel: Raw dataset source.

📁 Repository Contents
HR_Attrition_Analysis.pbix → The final Power BI report file.

HR_Employee_Attrition_Sample.xlsx → The dataset used for the analysis.

README.md → This project documentation.

📌 Internship Context
(Optional: If this project was for an internship or a specific program, you can add details here.)
This project was developed to demonstrate skills in:

End-to-end Power BI report development.

Data cleaning and transformation with Power Query.

Creating robust calculations with DAX.

Designing insightful and interactive dashboards for business stakeholders.

👤 Author
Aryan Roshan Patil

[LinkedIn][(https://www.linkedin.com/in/aryan-patil-245717286/)
