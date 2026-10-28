# TASK 9: HOUSE PRICE DATA ANALYSIS, PROPERTY FEATURE ENGINEERING & OUTLIER DETECTION

## PROJECT OVERVIEW

This project focuses on analyzing the King County House Sales dataset using Python, Pandas, NumPy, Matplotlib, and Seaborn. The dataset is analyzed to inspect property details, examine missing and duplicate values, extract sale years, calculate property age and renovation details, calculate price per square foot, visualize price distributions using box plots, and detect numerical outliers using the Interquartile Range (IQR) method. The processed dataset is finally saved as a CSV file for further analysis.

---

## OBJECTIVES

- Load the King County House Sales dataset.
- Inspect the dataset and display the first and last five records.
- Examine dataset information, statistical summary, shape, and column names.
- Check missing values and duplicate rows.
- Select important property features for analysis.
- Extract the sale year from the date column.
- Calculate property age at the time of sale.
- Identify the renovation status of properties.
- Calculate the number of years since renovation.
- Calculate price per square foot of living area and lot area.
- Visualize price per square foot distributions using box plots.
- Calculate Q1, Q3, IQR, lower bounds, and upper bounds for numerical columns.
- Identify numerical outliers using the IQR method.
- Display outlier analysis results.
- Save the processed dataset as a CSV file.

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

**DATASET NAME:** `kc_house_data.csv`

The dataset contains information such as:

- Date
- Price
- Bedrooms
- Bathrooms
- Living Area (`sqft_living`)
- Lot Area (`sqft_lot`)
- Grade
- Year Built (`yr_built`)
- Year Renovated (`yr_renovated`)
- Other property-related attributes

---

## PROJECT WORKFLOW

### STEP 1: IMPORT REQUIRED LIBRARIES

Import Pandas and NumPy for data processing and numerical calculations, Matplotlib for plotting, and Seaborn for statistical visualization.

### STEP 2: LOAD THE HOUSE SALES DATASET

Load the `kc_house_data.csv` file using Pandas and display the complete dataset.

### STEP 3: DISPLAY FIRST AND LAST FIVE ROWS

Display the first five and last five records to understand the structure and contents of the dataset.

### STEP 4: INSPECT DATASET INFORMATION

Display the dataset information, statistical summary, shape, and column names to understand its dimensions, data types, and numerical distributions.

### STEP 5: CHECK MISSING VALUES AND DUPLICATES

Check the dataset for missing values in each column and count the number of duplicate rows.

### STEP 6: SELECT PROPERTY FEATURES

Select important property attributes for analysis:

- Bedrooms
- Bathrooms
- Living Area
- Grade
- Year Built

Display the selected features for the first five records.

### STEP 7: EXTRACT SALE YEAR AND CALCULATE PROPERTY AGE

Extract the sale year from the date column and calculate property age by subtracting the year built from the sale year.

### STEP 8: CHECK RENOVATION STATUS

Create an `is_renovated` column to identify whether a property has been renovated based on the `yr_renovated` column.

- **Yes** – The property has a recorded renovation year greater than zero.
- **No** – The property has no recorded renovation year greater than zero.

### STEP 9: CALCULATE PRICE PER SQUARE FOOT

Calculate the price per square foot of living area by dividing the property price by the living area.

### STEP 10: CONVERT DATE AND CALCULATE AGE AT SALE

Convert the date column into a datetime format using error handling. Extract the sale year and calculate the property's age at the time of sale.

### STEP 11: CALCULATE YEARS SINCE RENOVATION

Calculate the difference between the sale year and renovation year for renovated properties. Assign zero to properties without a recorded renovation year.

### STEP 12: DISPLAY DATE AND AGE DETAILS

Display the date, sale year, year built, age at sale, renovation year, and years since renovation for the first five records.

### STEP 13: CALCULATE PRICE PER SQUARE FOOT OF LIVING AND LOT AREAS

Calculate two price-related measures:

- **Price per Square Foot of Living Area** – Property price divided by living area.
- **Price per Square Foot of Lot Area** – Property price divided by lot area.

Display the property price, living area, and lot area for the first five records.

### STEP 14: VISUALIZE PRICE PER SQUARE FOOT USING BOX PLOTS

Create separate box plots for price per square foot of living area and price per square foot of lot area using Seaborn and Matplotlib.

These visualizations help examine the distribution of property prices relative to area and identify potential extreme values.

### STEP 15: CALCULATE QUARTILES AND IQR

Calculate the first quartile (Q1), third quartile (Q3), and Interquartile Range (IQR) for numerical columns.

The following formulas are used:

- IQR = Q3 − Q1
- Lower Bound = Q1 − 1.5 × IQR
- Upper Bound = Q3 + 1.5 × IQR

### STEP 16: IDENTIFY NUMERICAL OUTLIERS

Select the numerical columns and identify values below the lower bounds or above the upper bounds using the IQR method.

### STEP 17: DISPLAY OUTLIER ANALYSIS

Display Q1, Q3, IQR, lower bounds, and upper bounds for the numerical columns. Calculate and display the number of rows containing at least one detected outlier.

### STEP 18: SAVE THE PROCESSED DATASET

Save the processed dataset, including the newly calculated features, as `kc_house_performance.csv` without writing the DataFrame index to the file.

---

## DATA ANALYSIS

- **Dataset Inspection** – Examine the dataset structure, data types, statistical summary, and dimensions.
- **Data Quality** – Check missing values and duplicate records.
- **Property Features** – Analyze bedrooms, bathrooms, living area, grade, and year built.
- **Sale Year** – Extract the year from the property sale date.
- **Property Age** – Calculate property age at the time of sale.
- **Renovation Status** – Classify properties according to their recorded renovation year.
- **Years Since Renovation** – Calculate the time elapsed since renovation for applicable properties.
- **Price per Square Foot** – Calculate property prices relative to living area and lot area.
- **Box Plot Visualization** – Examine price-per-square-foot distributions and potential extreme values.
- **Outlier Detection** – Identify numerical values outside the IQR-based bounds.
- **Processed Dataset** – Export the dataset with the calculated features to a CSV file.

---

## KEY ANALYSIS

- Inspect the King County House Sales dataset and understand its structure.
- Examine missing values and duplicate records.
- Select relevant property features for further analysis.
- Extract sale years and calculate property age at sale.
- Identify renovation status and calculate years since renovation.
- Compare property prices relative to living area and lot area.
- Visualize price-per-square-foot distributions using box plots.
- Calculate quartiles and IQR-based lower and upper bounds.
- Identify numerical outliers across the numerical columns.
- Count rows containing detected outliers.
- Save the processed dataset for future analysis.

---

## KEY OUTCOMES

- Successfully loaded and inspected the King County House Sales dataset.
- Examined dataset dimensions, data types, and statistical summaries.
- Checked missing values and duplicate records.
- Selected important property features for analysis.
- Extracted sale years from property sale dates.
- Calculated property age and age at sale.
- Identified property renovation status.
- Calculated years since renovation.
- Calculated price per square foot of living area and lot area.
- Created box plots to visualize price-per-square-foot distributions.
- Calculated Q1, Q3, IQR, and outlier bounds for numerical columns.
- Identified potential numerical outliers using the IQR method.
- Displayed the outlier analysis results.
- Exported the processed dataset as `kc_house_performance.csv`.

