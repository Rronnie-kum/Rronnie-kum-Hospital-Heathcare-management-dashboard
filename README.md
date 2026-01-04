Healthcare Management Dashboard | Power BI

Project Overview

In this project, I built an interactive Healthcare Management Dashboard using Power BI to analyze hospital performance from both operational and patient-centric perspectives.
The goal of this dashboard was to bring together patient data, departmental performance, and financial metrics into a single, easy-to-understand view for better decision-making.

Data Cleaning & Modeling

I started by cleaning and transforming the raw hospital data using Power Query. This included fixing data types, handling missing values, and standardizing fields such as departments, age groups, and feedback categories.
After cleaning, I created a well-structured data model with proper relationships so that all visuals respond accurately to filters and slicers.

KPIs & DAX Measures

I designed key hospital KPIs and calculated them using optimized DAX measures with variables (VAR) to keep the logic clear and efficient.
Some of the main KPIs include:

Total Patients (In-Patients and Out-Patients)
Total Revenue and Average Treatment Cost
Average ER Time
Patient-to-Staff Ratio
Bed Capacity vs Occupied Beds
Readmission Percentage
All measures are dynamic and update automatically based on selected month, department, or patient filters.

Hospital Operations Analysis

The dashboard provides a clear view of hospital operations by tracking:
Bed utilization, showing how much capacity is actually being used
Inflow vs Outflow patients, helping understand patient movement trends
ER waiting time by department, which helps identify operational bottlenecks
Month-wise trends to highlight peak and low activity periods
This section helps identify areas where operational efficiency can be improved.

Patient Demographics & Experience

To understand patient behavior and experience, I analyzed:
Patient distribution by age group and gender
Feedback categories ranging from fully satisfied to dissatisfied
The relationship between ER time and patient satisfaction
Readmission percentage as a quality indicator
These insights help evaluate both service quality and patient experience.

Department-Level Performance Insights

I created a dedicated Department Insights view to compare:
Patient volume across departments
Revenue contribution by each department
Average treatment cost versus ER time
Staff allocation between in-patients and out-patients
This makes it easy to identify high-performing departments as well as departments that need improvement.

Dashboard Design & Interactivity

I focused on keeping the dashboard clean, intuitive, and easy to navigate.
The dashboard includes:
KPI cards for quick performance tracking
Bar, line, donut, and scatter charts for comparison and trend analysis
Interactive slicers for month and department selection
Drill-through functionality to view individual patient details

Tools & Skills Used

Power BI Desktop
Power Query (ETL)
DAX (CALCULATE, FILTER, VAR, DIVIDE)
Data Modeling and Healthcare Analytics
