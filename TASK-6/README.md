# TASK 6: HEALTHCARE DATA VISUALIZATION, COST RELATIONSHIP & POLICY INSIGHTS

## PROJECT OVERVIEW

This project focuses on performing healthcare data visualization and analysis using Python, Pandas, Matplotlib, and Seaborn. The dataset is analyzed to compare billing amounts across medical conditions and insurance providers, visualize patient admission trends, analyze hospital stay duration, study relationships between age and medical costs, and prepare healthcare management recommendations.

---

## OBJECTIVES

- Load the healthcare dataset.
- Clean and prepare the required healthcare attributes.
- Convert the **Date of Admission** column into proper datetime format.
- Convert the **Billing Amount** column into numeric format.
- Remove records with missing required values.
- Build stacked bar charts comparing billing amounts across medical conditions and insurance providers.
- Create violin plots for billing amount distributions.
- Plot patient admission trends over time.
- Analyze monthly patient admission patterns.
- Calculate hospital stay duration.
- Generate a correlation matrix connecting Age, Stay Duration, and Total Medical Cost.
- Create a correlation heatmap.
- Prepare an executive summary with healthcare management recommendations.

---

## TECHNOLOGIES USED

- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn

---

## DATASET

**DATASET NAME:** `healthcare_dataset.csv`

The dataset contains information such as:

- Patient Information
- Medical Condition
- Date of Admission
- Discharge Date
- Admission Type
- Billing Amount
- Insurance Provider
- Age

---

## PROJECT WORKFLOW

### STEP 1: IMPORT REQUIRED LIBRARIES

Import the necessary Python libraries for data cleaning, analysis, statistical calculations, and visualization.

### STEP 2: LOAD THE HEALTHCARE DATASET

Load the `healthcare_dataset.csv` file using Pandas.

### STEP 3: CLEAN HEALTHCARE DATA

Clean the column names and prepare the required healthcare attributes for analysis.

### STEP 4: CONVERT DATE ATTRIBUTE

Convert the **Date of Admission** column into proper datetime format for temporal analysis.

### STEP 5: CONVERT BILLING AMOUNT

Convert the **Billing Amount** column into numeric format for accurate billing analysis.

### STEP 6: REMOVE MISSING REQUIRED VALUES

Remove records containing missing values in **Date of Admission, Billing Amount, Medical Condition, and Insurance Provider**.

### STEP 7: CREATE STACKED BAR CHART

Create a stacked bar chart to compare total **Billing Amount** across different **Medical Conditions** and **Insurance Providers**.

### STEP 8: CREATE VIOLIN PLOT BY MEDICAL CONDITION

Create a violin plot to analyze the distribution of **Billing Amount** across different medical conditions.

### STEP 9: CREATE VIOLIN PLOT BY INSURANCE PROVIDER

Create a violin plot to compare the distribution of **Billing Amount** across different insurance providers.

### STEP 10: VISUALIZE PATIENT ADMISSIONS OVER TIME

Group patient admissions by **Date of Admission** and create a temporal line chart to analyze admission trends.

### STEP 11: ANALYZE MONTHLY PATIENT ADMISSIONS

Extract the month from the admission date and create a line chart to analyze monthly patient admission trends.

### STEP 12: CALCULATE HOSPITAL STAY DURATION

Convert the **Discharge Date** column into datetime format and calculate hospital stay duration using the difference between discharge date and admission date.

### STEP 13: CREATE TOTAL MEDICAL COST

Create a new column named **Total Medical Cost** using the **Billing Amount** attribute.

### STEP 14: GENERATE CORRELATION MATRIX

Generate a correlation matrix using **Age, Stay Duration, and Total Medical Cost** to analyze relationships between these attributes.

### STEP 15: CREATE CORRELATION HEATMAP

Create a heatmap to visualize the correlation matrix between **Age, Stay Duration, and Total Medical Cost**.

### STEP 16: PREPARE EXECUTIVE SUMMARY

Calculate the average billing amount, average stay duration, and total number of admissions.

### STEP 17: PROVIDE HEALTHCARE MANAGEMENT RECOMMENDATIONS

Prepare recommendations based on billing patterns, insurance-wise differences, patient admission trends, stay duration, and medical cost relationships.

---

## DATA VISUALIZATIONS

- **Billing Amount by Medical Condition and Insurance Provider** – Stacked Bar Chart






<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/c317f4f2-1d61-472f-a4b3-043a26c1f989" />







- **Billing Amount by Medical Condition** – Violin Plot







<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/437aea61-f06e-46ff-b39e-ad278aab2832" />








- **Billing Amount by Insurance Provider** – Violin Plot







<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/e1958861-2cd6-46e9-a621-3a04e099d3aa" />






- **Patient Admissions Over Time** – Temporal Line Chart





  <img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/0e970695-408c-4cb5-984d-b78dc745641a" />






- **Monthly Patient Admissions** – Line Chart






<img width="1190" height="590" alt="image" src="https://github.com/user-attachments/assets/58ea3519-f963-4964-b411-dc33faa6eba3" />






- **Age, Stay Duration and Total Medical Cost** – Correlation Heatmap





<img width="645" height="490" alt="image" src="https://github.com/user-attachments/assets/ace26335-514f-4b10-a9a1-7e4a92b32286" />






---

## KEY ANALYSIS

- Compare billing amounts across different medical conditions and insurance providers.
- Analyze billing amount distributions using violin plots.
- Analyze patient admission trends over time.
- Analyze monthly patient admission patterns.
- Calculate hospital stay duration in days.
- Analyze the relationship between Age, Stay Duration, and Total Medical Cost.
- Identify relationships between healthcare cost and hospital stay duration.
- Prepare healthcare management recommendations based on the analysis.

---

## EXECUTIVE SUMMARY

- Calculate the average billing amount.
- Calculate the average hospital stay duration.
- Calculate the total number of admissions.
- Analyze billing differences across medical conditions and insurance providers.
- Monitor patient admission trends and monthly admission patterns.
- Analyze the relationship between stay duration and total medical cost.
- Support healthcare resource planning using admission and cost trends.
- Provide recommendations for healthcare management.

---

## KEY OUTCOMES

- Successfully loaded and cleaned the healthcare dataset.
- Converted date and billing attributes into appropriate formats.
- Removed records with missing required values.
- Compared billing amounts across medical conditions and insurance providers.
- Created stacked bar charts for billing analysis.
- Generated violin plots for billing amount distributions.
- Visualized patient admissions over time.
- Analyzed monthly patient admission trends.
- Calculated hospital stay duration.
- Generated a correlation matrix for Age, Stay Duration, and Total Medical Cost.
- Created a correlation heatmap.
- Prepared an executive summary with healthcare management recommendations.
