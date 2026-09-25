# TASK 3: STOCK MARKET PRICE, RETURN & TRADING VOLUME ANALYSIS

## PROJECT OVERVIEW
This project focuses on cleaning and performing exploratory analysis on the Apple Stock Market dataset using Python. The dataset is analyzed to clean stock price and trading volume attributes, calculate daily price changes and percentage returns, analyze trading volume trends, identify anomalous trading days, and summarize stock return distributions using statistical measures.

---

## OBJECTIVES
- Load the stock market dataset.
- Clean **Open, High, Low, Close, and Volume** attributes.
- Calculate daily price delta using **Close - Open**.
- Calculate daily percentage return.
- Analyze trading volume trends using a 5-day moving average.
- Identify anomalous trading days based on trading volume.
- Calculate mean, median, variance, and standard deviation of stock returns.
- Visualize trading volume trends and daily return distribution.

---

## TECHNOLOGIES USED
- Python
- Google Colab
- Pandas
- Matplotlib

---

## DATASET
**DATASET NAME:** `AAPL.xlsx`

The dataset contains information such as:
- Date
- Open Price
- High Price
- Low Price
- Close Price
- Trading Volume

---

## PROJECT WORKFLOW

### STEP 1: IMPORT REQUIRED LIBRARIES
Import the necessary Python libraries for data cleaning, analysis, and visualization.

### STEP 2: LOAD THE STOCK MARKET DATASET
Load the `AAPL.xlsx` file using Pandas.

### STEP 3: CLEAN PRICE ATTRIBUTES
Clean the column names and convert **Open, High, Low, Close, and Volume** columns into numeric format.

### STEP 4: CHECK FOR MISSING VALUES AND DUPLICATES
Identify missing values and duplicate records in the stock market dataset and remove them during data cleaning.

### STEP 5: CALCULATE DAILY PRICE DELTA
Calculate the daily price difference using **Close - Open** and create a new column named **Price_Delta**.

### STEP 6: CALCULATE DAILY PERCENTAGE RETURN
Calculate the daily percentage return using the Open and Close prices and create a new column named **Daily_Return**.

### STEP 7: CALCULATE TRADING VOLUME TREND
Calculate the **5-day moving average** of trading volume to analyze trading activity trends.

### STEP 8: IDENTIFY ANOMALOUS TRADING DAYS
Calculate the mean and standard deviation of trading volume and identify trading days with volume outside **±2 standard deviations** as anomalous days.

### STEP 9: CALCULATE STOCK RETURN STATISTICS
Calculate the following statistical measures for daily stock returns:
- Mean
- Median
- Variance
- Standard Deviation

### STEP 10: VISUALIZE TRADING VOLUME TREND
Create a line chart to visualize trading volume along with its 5-day moving average.

### STEP 11: VISUALIZE ANOMALOUS TRADING DAYS
Create a scatter plot to highlight anomalous trading days based on trading volume.

### STEP 12: VISUALIZE DAILY RETURN DISTRIBUTION
Create a histogram to analyze the distribution of daily stock returns.

### STEP 13: DISPLAY FINAL SUMMARY
Display the total number of clean records, average daily return, return variance, return standard deviation, average trading volume, and number of anomalous trading days.

---

## VISUALIZATIONS
- Line Chart: Trading Volume Trend with 5-Day Moving Average





<img width="989" height="490" alt="image" src="https://github.com/user-attachments/assets/753625c1-737a-40c4-bdd5-c88f0725e42c" />





- Scatter Plot: Anomalous Trading Days





<img width="989" height="490" alt="image" src="https://github.com/user-attachments/assets/2dc53b6f-b9ac-4130-a499-a55e50273e94" />






- Histogram: Daily Return Distribution




  <img width="789" height="490" alt="image" src="https://github.com/user-attachments/assets/7d4d0c1e-3ba7-4886-b82a-618f635e1bcf" />





---

## KEY OUTCOMES
- Successfully cleaned stock price and trading volume attributes.
- Calculated daily price delta.
- Calculated daily percentage return.
- Analyzed trading volume trends using a 5-day moving average.
- Identified anomalous trading days.
- Calculated mean, median, variance, and standard deviation of stock returns.
- Visualized trading volume trends and daily return distribution.
- Generated a final summary of stock returns and trading activity.

---
