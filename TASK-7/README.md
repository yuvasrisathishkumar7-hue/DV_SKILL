# TASK 7: STUDENT PERFORMANCE DATA CLEANING, STATISTICAL ANALYSIS & OUTLIER DETECTION

## PROJECT OVERVIEW

This project focuses on cleaning and analyzing the Student Performance dataset using Python, Pandas, and NumPy. The dataset is analyzed to clean categorical features, calculate statistical measures for Math, Reading, and Writing scores, calculate total marks and percentage performance, detect performance outliers, and display the final cleaned dataset.

---

## OBJECTIVES

- Load the Student Performance dataset.
- Inspect the dataset and identify missing values.
- Clean and standardize categorical attributes.
- Calculate mean, median, and standard deviation for subject scores.
- Calculate Q1 and Q3 for Math, Reading, and Writing scores.
- Calculate total marks for each student.
- Calculate percentage performance.
- Detect performance outliers using the IQR method.
- Display the final cleaned dataset.
- Display the final dataset shape.

---

## TECHNOLOGIES USED

- Python
- Google Colab
- Pandas
- NumPy

---

## DATASET

**DATASET NAME:** `StudentsPerformance.csv`

The dataset contains information such as:

- Gender
- Race/Ethnicity
- Parental Level Of Education
- Lunch
- Test Preparation Course
- Math Score
- Reading Score
- Writing Score

---

## PROJECT WORKFLOW

### STEP 1: IMPORT REQUIRED LIBRARIES

Import Pandas and NumPy libraries for data loading, cleaning, statistical analysis, and data processing.

### STEP 2: LOAD THE STUDENT PERFORMANCE DATASET

Load the `StudentsPerformance.csv` file using Pandas and display the first five records.

### STEP 3: CHECK MISSING VALUES

Check the dataset for missing values in all attributes.

### STEP 4: CLEAN CATEGORICAL FEATURES

Clean the categorical columns by removing extra spaces, standardizing column names, and replacing missing categorical values with **Unknown**.

The categorical attributes include:

- Gender
- Race/Ethnicity
- Parental Level Of Education
- Lunch
- Test Preparation Course

### STEP 5: CALCULATE SUBJECT SCORE STATISTICS

Calculate the following statistical measures for **Math Score, Reading Score, and Writing Score**:

- Mean
- Median
- Standard Deviation
- Q1
- Q3

### STEP 6: CALCULATE TOTAL MARKS

Calculate the total marks by adding the **Math Score, Reading Score, and Writing Score**.

### STEP 7: CALCULATE PERCENTAGE PERFORMANCE

Calculate the percentage performance using the total marks out of 300.

### STEP 8: DETECT PERFORMANCE OUTLIERS

Detect performance outliers for Math, Reading, and Writing scores using the **Interquartile Range (IQR)** method.

The lower and upper limits are calculated using:

- Lower Limit = Q1 - 1.5 × IQR
- Upper Limit = Q3 + 1.5 × IQR

### STEP 9: DISPLAY FINAL DATASET

Display the final dataset after performing the required cleaning and calculations.

### STEP 10: DISPLAY FINAL DATASET SHAPE

Display the number of rows and columns in the final dataset.

---

## DATA ANALYSIS

- **Categorical Features** – Clean and standardize student categorical attributes.
- **Math Score** – Calculate mean, median, standard deviation, Q1, and Q3.
- **Reading Score** – Calculate mean, median, standard deviation, Q1, and Q3.
- **Writing Score** – Calculate mean, median, standard deviation, Q1, and Q3.
- **Total Marks** – Calculate the combined marks of all three subjects.
- **Percentage** – Calculate student percentage based on total marks.
- **Performance Outliers** – Identify unusual subject scores using the IQR method.

---

## KEY ANALYSIS

- Inspect the Student Performance dataset and identify missing values.
- Clean and standardize categorical features.
- Analyze the statistical distribution of Math, Reading, and Writing scores.
- Compare the mean, median, and standard deviation of subject scores.
- Calculate Q1 and Q3 for each subject.
- Calculate total marks for each student.
- Calculate overall percentage performance.
- Identify performance outliers using the IQR method.
- Display the final cleaned dataset and its shape.

---

## KEY OUTCOMES

- Successfully loaded and inspected the Student Performance dataset.
- Identified missing values in the dataset.
- Cleaned and standardized categorical features.
- Replaced missing categorical values with **Unknown**.
- Calculated mean, median, and standard deviation for subject scores.
- Calculated Q1 and Q3 for Math, Reading, and Writing scores.
- Calculated total marks for each student.
- Calculated percentage performance.
- Detected performance outliers using the IQR method.
- Displayed the final cleaned dataset.
- Displayed the final dataset shape.
