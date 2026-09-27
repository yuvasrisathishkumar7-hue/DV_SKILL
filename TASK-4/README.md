# TASK 4: STOCK MARKET PRICE, MOVING AVERAGE & RETURN ANALYSIS

## PROJECT OVERVIEW

This project focuses on performing exploratory analysis on the Shopify Stock Market dataset using Python. The dataset is analyzed to visualize OHLC prices and trading volume, calculate daily returns, analyze 20-day and 50-day moving averages, study daily return distributions using histogram and KDE plots, identify high-volatility days, and prepare a financial summary report.

---

## OBJECTIVES

- Load the stock market dataset.
- Clean **Open, High, Low, Close, and Volume** attributes.
- Convert the **Date** column into proper datetime format.
- Calculate daily percentage return using Open and Close prices.
- Build line plots for OHLC prices over time.
- Visualize trading volume trends over time.
- Calculate 20-day and 50-day moving averages.
- Plot daily closing prices with 20-day and 50-day moving averages.
- Generate histogram and KDE plots for daily returns.
- Calculate mean, variance, and standard deviation of daily returns.
- Identify high-volatility days using ±2 standard deviations.
- Prepare a financial summary report for stock stability and volatility.

---

## TECHNOLOGIES USED

- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn

---

## DATASET

**DATASET NAME:** `shopify_stock.csv`

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

Import the necessary Python libraries for data cleaning, analysis, statistical calculations, and visualization.

### STEP 2: LOAD THE STOCK MARKET DATASET

Load the `shopify_stock.csv` file using Pandas.

### STEP 3: CLEAN STOCK MARKET DATA

Clean the column names and convert the **open, high, low, close, and volume** columns into numeric format.

### STEP 4: CHECK FOR MISSING VALUES AND DUPLICATES

Remove records containing missing values in the required stock attributes and remove duplicate records.

### STEP 5: CONVERT AND SORT DATE

Convert the **Date** column into datetime format and sort the dataset based on the date.

### STEP 6: CALCULATE DAILY RETURNS

Calculate daily percentage returns using the Open and Close prices and create a new column named **Daily_Return**.

### STEP 7: VISUALIZE OHLC PRICES

Create a line plot for **Open, High, Low, and Close** prices to analyze stock price movements over time.

### STEP 8: VISUALIZE TRADING VOLUME

Create a line plot to analyze trading volume trends over time.

### STEP 9: CALCULATE 20-DAY MOVING AVERAGE

Calculate the **20-day moving average** of the closing price to analyze short-term price trends.

### STEP 10: CALCULATE 50-DAY MOVING AVERAGE

Calculate the **50-day moving average** of the closing price to analyze long-term price trends.

### STEP 11: COMPARE CLOSING PRICE WITH MOVING AVERAGES

Plot the daily closing price together with the **20-day and 50-day moving averages** to analyze price trends.

### STEP 12: GENERATE DAILY RETURN HISTOGRAM AND KDE

Create a histogram with KDE to visualize the distribution and shape of daily stock returns.

### STEP 13: CALCULATE RETURN STATISTICS

Calculate the following statistical measures:

- Mean Return
- Variance
- Standard Deviation

### STEP 14: IDENTIFY HIGH-VOLATILITY DAYS

Identify high-volatility days where the absolute daily return is greater than **2 standard deviations** from the return distribution.

### STEP 15: PREPARE FINANCIAL SUMMARY REPORT

Generate a financial summary containing return statistics, price statistics, trading volume information, high-volatility days, and an interpretation of stock stability.

---

## VISUALIZATIONS

- Line Chart: OHLC Prices Over Time




<img width="889" height="426" alt="image" src="https://github.com/user-attachments/assets/94d87ec9-7cd9-425e-b114-01b7de3e83eb" />




- Line Chart: Trading Volume Over Time




<img width="884" height="365" alt="image" src="https://github.com/user-attachments/assets/3be27315-fae6-42f3-9f67-1a7e4e372ee9" />





- Line Chart: Closing Price with 20-Day and 50-Day Moving Averages




<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/85e0b06f-6646-401e-9eea-ade37a433963" />




- Histogram and KDE: Daily Return Distribution




<img width="630" height="470" alt="image" src="https://github.com/user-attachments/assets/f5b993af-76d2-434b-bab9-a406fabe0cd7" />




---

## FINANCIAL SUMMARY

- Calculate the mean daily return.
- Calculate return variance and standard deviation.
- Identify the highest and lowest closing prices.
- Calculate average and maximum trading volume.
- Identify high-volatility days using the ±2 standard deviation method.
- Analyze overall stock return variation.
- Interpret stock stability based on the standard deviation of daily returns.

---

## KEY OUTCOMES

- Successfully cleaned the Shopify stock market dataset.
- Converted and sorted the Date column.
- Calculated daily percentage returns.
- Visualized OHLC prices over time.
- Analyzed trading volume trends.
- Calculated 20-day and 50-day moving averages.
- Compared closing prices with moving averages.
- Generated histogram and KDE plots for daily returns.
- Calculated mean, variance, and standard deviation of returns.
- Identified high-volatility days using ±2 standard deviations.
- Generated a financial summary report describing stock stability and volatility.
