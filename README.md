Index
Project Overview
Objective
Tools
Deliverables
Data Sources
Healthcare Dataset 1
Healthcare Dataset 2
Data Preparation
Data Cleansing
Data Transformation
Power BI Report Structure
Patients Info Dashboard
Charts
Key Insights Findings
Hospitals and Cost Dashboard
Charts
Key Insights Findings
Diagnosis and Treatment Dashboard
Charts
Key Insights Findings
QA Page
Future Enhancements
Conclusion
Project Overview
Objective
The Healthcare Data Analysis project leverages Power BI to analyze and extract meaningful insights from healthcare datasets. The aim is to uncover trends, patterns, and correlations to enhance decision-making and operational efficiency in healthcare organizations. Interactive dashboards will showcase key metrics like patient demographics, treatment effectiveness, hospital utilization, and cost management.

Deliverables
Patient-Centric Analysis:
Insights on patient demographics, diagnoses, treatments, and medical expenses.
Hospital-Centric Analysis:
Insights into hospital performance, recovery ratings, room costs, and staff evaluations.
Dashboards:
Interactive visual dashboards to support data-driven decisions.
Data Quality Checks:
Address missing, inconsistent, or inaccurate data points for robust analysis.
Data Sources
Healthcare Dataset 1: Patient-Centric Dataset
Key columns:

Patient ID
Age, Gender, and Blood Type
Diagnosis and Treatment
Admission and Discharge Dates
Total Bill
Full Prescription Details
Healthcare Dataset 2: Hospital-Centric Dataset
Key columns:

Patient ID
Hospital Name
Recovery Ratings
Room Type and Costs
Data Preparation
Data Cleansing
Inconsistent Date Formats: Standardized dates to YYYY-MM-DD.
Full Prescription Details: Extracted relevant medication names and doses.
Missing Values:
Patient Names: Marked as "Unknown" where data was unavailable.
Total Bill: Imputed with averages for similar cases.
Data Transformation
Created new metrics such as:
LengthOfStay: Calculated using Admission and Discharge Dates.
AgeGroup: Categorized into Child, Teenage, Adult, and Senior.
Merged datasets on Patient ID using a full outer join in Power Query.
Power BI Report Structure
1. Patients Info Dashboard
Charts:
Patient demographics (age groups, gender distribution).
Diagnosis and treatment types.
Key Insights Findings:
Treatment patterns by age group.
Distribution of medical conditions.
2. Hospitals and Cost Dashboard
Charts:
Room costs vs recovery ratings.
Hospital utilization rates.
Key Insights Findings:
Cost trends for extended stays.
Hospital performance comparisons.
3. Diagnosis and Treatment Dashboard
Charts:
Diagnosis frequency by demographics.
Treatment effectiveness (recovery rates).
Key Insights Findings:
Common treatments for specific conditions.
Recovery rate trends by hospital.
QA Page
Summarized testing steps and validation outcomes to ensure data accuracy and reliable insights.
Future Enhancements
Integrate real-time data from healthcare systems.
Add predictive analysis for patient outcomes using AI.
Develop mobile-compatible dashboards.
Conclusion
This project demonstrates the power of Power BI in simplifying complex healthcare data into actionable insights. These dashboards will assist healthcare organizations in improving operational efficiency, patient care, and cost management.
