# TASK 1: SUPERSTORE SALES DATA UNDERSTANDING, CLEANING & EXPLORATORY ANALYSIS

## PROJECT OVERVIEW
This project focuses on understanding, cleaning, and performing exploratory analysis on the Superstore Sales dataset using Python. The dataset is analyzed to inspect its structure, clean categorical data, convert date columns into datetime format, calculate delivery time, and generate summary statistics and visualizations.

---

## OBJECTIVES
- Load the Superstore Sales dataset.
- Inspect the dataset using `head()`, `info()`, and `describe()`.
- Convert **Order Date** and **Ship Date** into datetime format.
- Calculate delivery days.
- Check for missing values.
- Explore unique values in categorical columns.
- Calculate total sales by category.
- Visualize sales distribution and category-wise sales.

---

## TECHNOLOGIES USED
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## DATASET
**DATASET NAME:** `SampleSuperstore.csv`

The dataset contains information such as:
- Order Details
- Customer Information
- Product Details
- Sales
- Profit
- Quantity
- Discount
- Shipping Details

---

## PROJECT WORKFLOW

### STEP 1: IMPORT REQUIRED LIBRARIES
Import the necessary Python libraries for data analysis and visualization.

### STEP 2: LOAD THE SUPERSTORE DATASET
Load the CSV file using Pandas.

### STEP 3: DISPLAY THE FIRST FIVE ROWS
View the first five records using `head()`.

### STEP 4: DISPLAY DATASET INFORMATION
Inspect column names, data types, and missing values using `info()`.

### STEP 5: DISPLAY DESCRIPTIVE STATISTICS
Generate summary statistics for numerical columns using `describe()`.

### STEP 6: CONVERT DATE COLUMNS
Convert **Order Date** and **Ship Date** into datetime format.

### STEP 7: VERIFY UPDATED DATA TYPES
Confirm the successful conversion of date columns.

### STEP 8: CALCULATE DELIVERY DAYS
Create a new column named **Delivery Days**.

### STEP 9: DISPLAY THE UPDATED DATASET
Preview the dataset after adding the new column.

### STEP 10: DISPLAY UNIQUE VALUES
View the unique values in the **Category** column.

### STEP 11: CHECK FOR MISSING VALUES
Identify missing values using `isnull().sum()`.

### STEP 12: CALCULATE TOTAL SALES BY CATEGORY
Compute the total sales for each product category.

### STEP 13: VISUALIZE TOTAL SALES BY CATEGORY
Create a bar chart to compare category-wise sales.

### STEP 14: VISUALIZE THE DISTRIBUTION OF SALES
Create a histogram to analyze the sales distribution.

---

## VISUALIZATIONS
- Bar Chart: Total Sales by Category
- Histogram: Sales Distribution

---

## KEY OUTCOMES
- Successfully explored and understood the dataset.
- Converted date columns into datetime format.
- Calculated delivery duration.
- Identified missing values.
- Generated descriptive statistics.
- Analyzed sales by category.
- Created informative visualizations for business insights.

---
