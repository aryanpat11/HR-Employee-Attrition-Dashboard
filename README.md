# 📊 HR Employee Attrition Dashboard  

This repository contains my **HR Employee Attrition Analysis** project, where I explored a sample HR dataset using **Microsoft Power BI**.  
The goal was to build an **interactive dashboard** that uncovers key factors driving employee attrition, helping HR departments make **data-driven decisions** to improve retention strategies.  

---

## 📂 Project Overview  

- **Domain**: HR Analytics / People Analytics  
- **Tool Used**: Microsoft Power BI  
- **Dataset**: HR Employee Attrition Sample (.xlsx)  
- **Output**: Interactive Power BI Report (.pbix)  

---

## 🔧 Project Workflow  

### 1. Data Cleaning & Transformation (Power Query)  
✔ Corrected data types (e.g., Age, MonthlyIncome).  
✔ Removed duplicates to ensure data integrity.  
✔ Trimmed & standardized text columns (Department, JobRole).  
✔ Created calculated column **AttritionFlag** (1 = Yes, 0 = No).  
✔ Added custom columns: **AnnualIncome** & **AgeGroup** for deeper insights.  

### 2. Data Modeling & DAX Measures  
Developed core DAX measures to power the dashboard visuals:  
- **Total Employees** = `COUNTROWS('Employees')`  
- **Attrition Count** = `SUM('Employees'[AttritionFlag])`  
- **Attrition Rate** = `DIVIDE([Attrition Count], [Total Employees])`  
- **Avg Monthly Income** = `AVERAGE('Employees'[MonthlyIncome])`  

### 3. Visualization & Dashboard Design  
- **Overview Page**: High-level summary with KPIs.  
- **KPI Cards**: Total Employees | Attrition Rate | Avg Monthly Income | Avg Annual Income.  
- **Charts**:  
  - Bar: Attrition by Department & Job Role.  
  - Donut: Attrition by Gender.  
  - Column: Attrition by Age Group.  
- **Interactive Features**: Slicers (Department, JobRole, Gender) & Drillthrough to employee-level details.  

---

## 💡 Key Insights  

- 🚨 **High Attrition Rate**: 47% — a critical HR challenge.  
- 👔 **Managers** face the highest attrition → Possible leadership or growth issues.  
- 👨‍👩‍👧 **Age 31–40 group** shows the most exits → Career building phase risk.  
- 📈 **Marketing Department** has the most departures.  

---

## 📸 Dashboard Snapshots  
<img width="1320" height="738" alt="image" src="https://github.com/user-attachments/assets/8503fa26-fa3f-41fe-9197-ee7529a7d3b2" />
<img width="1263" height="446" alt="image" src="https://github.com/user-attachments/assets/cdcc19ee-6186-4cf9-8c8f-4eb975193197" />



---

## 🛠️ Tools & Technologies  

- **Power BI Desktop** → Data visualization, modeling & dashboard design.  
- **Power Query** → Data cleaning & transformation (ETL).  
- **DAX (Data Analysis Expressions)** → Custom calculations & measures.  
- **Excel** → Source dataset.  

---

## 📁 Repository Contents  

- `HR_Attrition_Analysis.pbix` → Final Power BI report.  
- `HR_Employee_Attrition_Sample.xlsx` → Dataset used.  
- `README.md` → Project documentation.  

---

## 📌 Internship / Learning Context  

This project demonstrates my ability in:  
- End-to-end **Power BI dashboard development**.  
- **Data cleaning & transformation** with Power Query.  
- Building **robust DAX calculations**.  
- Designing **interactive dashboards** for stakeholders.  

---

## 👤 Author  

**Aryan Roshan Patil**  
[LinkedIn](https://www.linkedin.com/in/aryan-patil-245717286/)  
