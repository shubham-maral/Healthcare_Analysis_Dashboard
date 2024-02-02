**Healthcare Data Analysis Project**

**Case Study: Advancing Healthcare Analysis through Data Insights**


**Background**
You are a data analyst at HealthStat Solutions, a company specializing in healthcare analytics. You have been given two datasets: 'Patient Medical Records' and 'Hospital Treatment Details'. The 'Patient Medical Records' dataset contains detailed information on patients, including their age, gender, blood type, diagnosis, treatments, admission and discharge dates, and total bills. The 'Hospital Treatment Details' dataset provides insights into the hospitals treating these patients, including the treating doctor, room number, daily costs, treatment types, and recovery ratings.

In a healthcare industry that relies heavily on data to make informed decisions for patient care and hospital management, your role is crucial. Your task is to analyze these datasets, uncovering trends and insights that could improve patient outcomes and optimize hospital operations.


**Objective**
As an analyst at HealthStat Solutions, your objective is to leverage Power BI for a deep dive into the provided healthcare datasets. This task encompasses meticulous data cleaning and sophisticated data modeling, utilizing DAX for advanced analytics. Your goal is to create a comprehensive, interactive dashboard in Power BI that presents a cohesive narrative of the healthcare data. This dashboard should serve as a tool to uncover and visualize important trends, such as the interplay between patient demographics and treatment outcomes, cost implications of various medical procedures, and overall hospital performance metrics. Your analysis will provide invaluable insights, aiding healthcare providers in enhancing patient care and operational efficiency, and positioning HealthStat Solutions at the forefront of healthcare analytics.


**Data Source:**

[HealthcareDataset1.xlsx](https://prod-files-secure.s3.us-west-2.amazonaws.com/d1e1bc70-9ede-4c69-84fd-42c5605803a0/f612ea2d-d0ea-4f03-9d9e-056baa3a6658/HealthcareDataset1.xlsx)

The 'HealthcareDataset1.xlsx' file contains the following columns:
1. **PatientID**: A unique identifier for each patient. (Primary Key)
2. **PatientName**: Name of the patient.
3. **Age**: Age of the patient.
4. **Gender**: Gender of the patient.
5. **BloodType**: Blood type of the patient.
6. **Diagnosis**: The diagnosis given to the patient.
7. **Treatment**: The treatment provided to the patient.
8. **AdmissionDate**: Date when the patient was admitted.
9. **DischargeDate**: Date when the patient was discharged.
10. **TotalBill**: The total bill amount for the patient's treatment.
11. **Full Prescription Details**: Detailed prescription information including medication names, dosages, frequency, and duration

[HealthcareDataset2.xlsx](https://prod-files-secure.s3.us-west-2.amazonaws.com/d1e1bc70-9ede-4c69-84fd-42c5605803a0/78856dc5-afc4-4b4d-a42d-f75a0affd3d7/HealthcareDataset2.xlsx)

The 'HealthcareDataset2.xlsx' file contains the following columns:
1. **PatientID**: A unique identifier for each patient, corresponding to 'PatientID' in 'HealthcareDataset1.xlsx'. (Foreign Key)
2. **Hospital**: The name of the hospital where the patient was treated.
3. **DoctorName**: Name of the doctor who treated the patient.
4. **RoomNumber**: The room number assigned to the patient.
5. **DailyCost**: The daily cost of the patient's treatment.
6. **TreatmentType**: Type of treatment provided.
7. **RecoveryRating**: A rating of the patient's recovery (out of 10).


**Part 1: Data Cleaning, Modeling, and DAX in Power BI**
- Data Importing and Initial Examination
- Merging and Relating Datasets
- Cleaning: Handling Missing and Irrelevant Data
- Data Type Conversion
- Categorizing Age Groups
- Analysis of Treatment Costs
- Gender Distribution in Diagnosis
- Blood Type Analysis
- Recovery Rating Analysis
- Hospital Utilization Analysis
- Doctor's Patient Load
- Treatment Effectiveness
- Cost Analysis by Hospital
- Patient Admission Trends Over Time
- Correlation Between Age and Recovery
- Analyzing Room Efficiency
- Impact of Doctor on Recovery
- Advanced DAX: Length of Stay and Cost Correlation
- Recovery Trends by Gender and Age Group
- Hospital Performance Analysis
- Extracting Key Information
- Complex DAX: Predictive Modeling for Recovery Rating
- Data Modeling: Cohort Analysis Based on Admission Date
- Advanced Data Transformation: Predicting Future Hospital Capacity Needs

  
**Part 2: Dashboard Building**
- Comprehensive Healthcare Dashboard
- Design and Usability
- Time-Based Analysis in Dashboard
- Interactive Hospital Performance Comparison
- Treatment Effectiveness Visualization
- Key Insights and Data Storytelling
