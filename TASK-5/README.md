# TASK 5: HEALTHCARE DATA CLEANING, ADMISSION ANALYSIS & DEMOGRAPHIC SEGMENTATION

## PROJECT OVERVIEW

This project focuses on understanding, cleaning, and analyzing the Healthcare dataset using Python and Pandas. The dataset is analyzed to inspect the data, clean missing medical conditions, standardize admission and discharge dates, categorize admissions by urgency, calculate hospital stay duration, analyze billing amounts, and segment patient demographics by medical condition.

---

## OBJECTIVES

- Load the healthcare dataset using Pandas.
- Inspect the dataset using `head()`, `shape`, `info()`, and missing value analysis.
- Clean missing values in the **Medical Condition** attribute.
- Standardize **Date of Admission** and **Discharge Date** attributes.
- Categorize admissions into **Emergency, Elective, and Urgent**.
- Calculate hospital stay duration in days.
- Calculate summary statistics for **Billing Amount**.
- Calculate summary statistics for **Hospital Stay Days**.
- Segment patient demographics by **Medical Condition**.
- Display the final cleaned dataset and its shape.

---

## TECHNOLOGIES USED

- Python
- Google Colab
- Pandas

---

## DATASET

**DATASET NAME:** `healthcare_dataset.csv`

The dataset contains healthcare-related information such as:

- Patient Information
- Medical Condition
- Date of Admission
- Discharge Date
- Admission Type
- Billing Amount
- Age

---

## PROJECT WORKFLOW

### STEP 1: IMPORT REQUIRED LIBRARIES

Import the Pandas library for data loading, cleaning, transformation, grouping, and statistical analysis.

### STEP 2: LOAD THE HEALTHCARE DATASET

Load the `healthcare_dataset.csv` file using Pandas and display the first five records.

### STEP 3: INSPECT THE DATASET

Check the dataset shape, column information, and missing values to understand the structure and quality of the data.

### STEP 4: CLEAN MISSING MEDICAL CONDITIONS

Replace missing values in the **Medical Condition** column with **Unknown**.

### STEP 5: STANDARDIZE DATE ATTRIBUTES

Convert the **Date of Admission** and **Discharge Date** columns into proper datetime format.

### STEP 6: CATEGORIZE ADMISSIONS BY URGENCY

Create a new **Urgency** column and categorize admission types as:

- Emergency
- Elective
- Urgent

Other admission types are categorized as **Unknown**.

### STEP 7: CALCULATE HOSPITAL STAY

Calculate the number of hospital stay days by finding the difference between **Discharge Date** and **Date of Admission**.

### STEP 8: ANALYZE BILLING AMOUNT

Generate descriptive statistics for the **Billing Amount** column.

### STEP 9: ANALYZE HOSPITAL STAY

Generate descriptive statistics for the calculated **Hospital Stay Days** column.

### STEP 10: SEGMENT DEMOGRAPHICS BY MEDICAL CONDITION

Group patients based on **Medical Condition** and calculate:

- Patient Count
- Average Age
- Minimum Age
- Maximum Age

### STEP 11: DISPLAY FINAL CLEANED DATA

Display the final cleaned dataset and its shape after performing the required data cleaning and transformations.

---

## DATA ANALYSIS

- **Admission Urgency** – Count Emergency, Elective, and Urgent admissions.
- **Billing Amount** – Generate descriptive statistics using `describe()`.
- **Hospital Stay Days** – Calculate and summarize hospital stay duration.
- **Medical Condition** – Group patients based on their medical condition.
- **Age Demographics** – Calculate count, mean, minimum, and maximum age for each medical condition.

---

## KEY ANALYSIS

- Inspect the healthcare dataset and identify missing values.
- Clean missing values in the Medical Condition attribute.
- Convert admission and discharge dates into datetime format.
- Categorize admissions based on their admission type.
- Calculate hospital stay duration in days.
- Analyze patient billing amounts using descriptive statistics.
- Analyze hospital stay duration using descriptive statistics.
- Segment patient age demographics by medical condition.
- Display the final cleaned dataset and dataset shape.

---

## KEY OUTCOMES

- Successfully loaded and inspected the healthcare dataset.
- Identified missing values in the dataset.
- Replaced missing Medical Condition values with **Unknown**.
- Standardized Date of Admission and Discharge Date attributes.
- Categorized admissions into Emergency, Elective, and Urgent.
- Calculated hospital stay duration in days.
- Generated billing amount statistics.
- Generated hospital stay statistics.
- Segmented patient demographics by medical condition.
- Displayed the final cleaned dataset and its shape.
