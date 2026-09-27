# WEEK 1: SUPERSTORE SALES DATA UNDERSTANDING, CLEANING & EXPLORATORY ANALYSIS

## DESCRIPTION

This task focuses on understanding, cleaning, and analyzing the Superstore Sales dataset using Python and Pandas.

## OBJECTIVES

* Load the dataset using Pandas.
* Inspect the dataset using `head()`, `info()`, and `describe()`.
* Convert Order Date and Ship Date columns into proper datetime format.
* Clean and standardize categorical attributes such as Category, Sub-Category, and Segment.
* Calculate initial summary statistics for numerical attributes.

## WORKFLOW

```mermaid
flowchart TD
    A[LOAD DATASET] --> B[DATA INSPECTION]
    B --> C[DATE FORMAT CONVERSION]
    C --> D[CATEGORICAL DATA CLEANING]
    D --> E[SUMMARY STATISTICS CALCULATION]
    E --> F[EXPLORATORY DATA ANALYSIS]
    F --> G[INSIGHTS GENERATION]
```

# WEEK 2: RETAIL SALES VISUALIZATION, RELATIONSHIP ANALYSIS & BUSINESS INSIGHTS

## DESCRIPTION

This task focuses on visualizing retail sales and analyzing relationships between Sales, Profit, Discount, Quantity, and other numerical attributes using Python, Matplotlib, and Seaborn.

## OBJECTIVES

* Create bar plots, histograms, and box plots to visualize sales and profit.
* Analyze the relationship between Discount and Profit.
* Identify discount levels that negatively affect profitability.
* Generate a correlation heatmap for numerical attributes.
* Analyze relationships between Sales, Profit, Discount, and Quantity.
* Generate meaningful business insights from the visualizations.
* Prepare the findings as a 1-page survey report.

## WORKFLOW

```mermaid
flowchart TD
    A[LOAD CLEANED DATASET] --> B[CREATE BAR PLOTS]
    B --> C[CREATE HISTOGRAM]
    C --> D[CREATE BOX PLOTS]
    D --> E[ANALYZE DISCOUNT VS PROFIT]
    E --> F[GENERATE CORRELATION MATRIX]
    F --> G[CREATE CORRELATION HEATMAP]
    G --> H[IDENTIFY BUSINESS INSIGHTS]
    H --> I[PREPARE 1-PAGE SURVEY REPORT]
```

## VISUALIZATIONS

* **Sales by Category** – Bar Plot
* **Sales Distribution** – Histogram
* **Profit by Category** – Bar Plot
* **Sales Distribution by Category** – Bar Plot
* **Profit Variation Across Categories** – Box Plot
* **Profit Distribution** – Box Plot
* **Discount vs Profit** – Scatter Plot
* **Correlation Heatmap** – Heatmap

## BUSINESS INSIGHTS

* Analyze the impact of discounts on profitability.
* Compare sales and profit across different categories.
* Identify relationships between numerical attributes.
* Identify strong and weak-performing categories.
* Support better pricing and discount decisions using data analysis.

## KEY OUTCOMES

* Visualized retail sales and profit using different plots.
* Analyzed the distribution of Sales and Profit.
* Compared sales and profit across different categories.
* Analyzed the relationship between Discount and Profit.
* Identified discount levels that may negatively affect profitability.
* Generated a correlation heatmap for numerical attributes.
* Identified important relationships between Sales, Profit, Discount, and Quantity.
* Extracted meaningful business insights.
* Prepared the findings as a 1-page survey report.



# WEEK 3: STOCK MARKET PRICE, RETURN & TRADING VOLUME ANALYSIS

## DESCRIPTION

This task focuses on cleaning and analyzing stock market data using Python and Pandas. The dataset is analyzed to calculate daily price changes and percentage returns, study trading volume trends, identify anomalous trading days, and summarize stock return distributions using statistical measures.

## OBJECTIVES

* Load the stock market dataset using Pandas.
* Clean the **Open, High, Low, Close, and Volume** attributes.
* Calculate daily price delta using **Close - Open**.
* Calculate daily percentage return.
* Calculate the 5-day moving average of trading volume.
* Identify anomalous trading days based on trading volume.
* Calculate mean, median, variance, and standard deviation of stock returns.
* Visualize trading volume trends and daily return distribution.
* Generate a final summary of stock returns and trading activity.

## WORKFLOW

```mermaid
flowchart TD
    A[LOAD DATASET] --> B[DATA CLEANING]
    B --> C[CALCULATE PRICE DELTA]
    C --> D[CALCULATE DAILY RETURN]
    D --> E[ANALYZE TRADING VOLUME]
    E --> F[IDENTIFY ANOMALOUS DAYS]
    F --> G[CALCULATE RETURN STATISTICS]
    G --> H[VISUALIZE RETURN DISTRIBUTION]
    H --> I[GENERATE FINAL SUMMARY]
```

## VISUALIZATIONS

* **Trading Volume Trend** – Line Chart
* **5-Day Moving Average of Volume** – Line Chart
* **Anomalous Trading Days** – Line + Scatter Plot
* **Daily Return Distribution** – Histogram

## STATISTICAL ANALYSIS

* **Mean** – Average daily stock return.
* **Median** – Middle value of daily returns.
* **Variance** – Measures the spread of daily returns.
* **Standard Deviation** – Measures the volatility of daily returns.

## KEY ANALYSIS

* Analyze daily price changes using Open and Close prices.
* Measure daily percentage returns.
* Analyze trading volume trends using a 5-day moving average.
* Detect unusually high or low trading volume days.
* Analyze the distribution and variation of daily stock returns.
* Summarize stock return and trading volume characteristics.

## KEY OUTCOMES

* Successfully cleaned the stock market price and volume attributes.
* Calculated daily price delta using Open and Close prices.
* Calculated daily percentage returns.
* Analyzed trading volume using a 5-day moving average.
* Identified anomalous trading days using volume statistics.
* Calculated mean, median, variance, and standard deviation of stock returns.
* Visualized trading volume trends and daily return distribution.
* Generated a final summary of stock returns and trading activity.



# WEEK 4: STOCK MARKET PRICE, MOVING AVERAGE & RETURN ANALYSIS

## DESCRIPTION

This task focuses on analyzing Shopify stock market data using Python, Pandas, Matplotlib, and Seaborn. The dataset is analyzed to visualize OHLC prices and trading volume, calculate daily percentage returns, study 20-day and 50-day moving averages, analyze daily return distributions using histogram and KDE plots, identify high-volatility days, and prepare a financial summary report.

## OBJECTIVES

* Load the Shopify stock market dataset using Pandas.
* Clean the **Open, High, Low, Close, and Volume** attributes.
* Calculate daily percentage returns using Open and Close prices.
* Create line plots for Open, High, Low, and Close prices over time.
* Visualize trading volume trends over time.
* Calculate 20-day and 50-day moving averages of closing prices.
* Compare daily closing prices with 20-day and 50-day moving averages.
* Generate histogram and KDE plots for daily returns.
* Calculate mean, variance, and standard deviation of stock returns.
* Identify high-volatility days using the ±2 standard deviation method.
* Prepare a financial summary report describing stock stability and volatility.

## WORKFLOW

```mermaid
flowchart TD
    A[LOAD DATASET] --> B[DATA CLEANING]
    B --> C[CALCULATE DAILY RETURNS]
    C --> D[VISUALIZE OHLC PRICES]
    D --> E[ANALYZE TRADING VOLUME]
    E --> F[CALCULATE 20-DAY MOVING AVERAGE]
    F --> G[CALCULATE 50-DAY MOVING AVERAGE]
    G --> H[COMPARE CLOSING PRICE WITH MOVING AVERAGES]
    H --> I[VISUALIZE RETURN DISTRIBUTION]
    I --> J[CALCULATE RETURN STATISTICS]
    J --> K[IDENTIFY HIGH-VOLATILITY DAYS]
    K --> L[GENERATE FINANCIAL SUMMARY]
````

## VISUALIZATIONS

* **OHLC Prices Over Time** – Line Chart
* **Trading Volume Over Time** – Line Chart
* **Closing Price with 20-Day Moving Average** – Line Chart
* **Closing Price with 50-Day Moving Average** – Line Chart
* **Closing Price with 20-Day and 50-Day Moving Averages** – Line Chart
* **Daily Return Distribution** – Histogram and KDE Plot

## STATISTICAL ANALYSIS

* **Mean** – Average daily stock return.
* **Variance** – Measures the spread of daily stock returns.
* **Standard Deviation** – Measures the variation in daily stock returns.
* **Highest Closing Price** – Maximum closing price recorded in the dataset.
* **Lowest Closing Price** – Minimum closing price recorded in the dataset.
* **Average Trading Volume** – Average trading volume during the period.
* **Maximum Trading Volume** – Highest trading volume recorded in the dataset.

## KEY ANALYSIS

* Analyze stock price movements using Open, High, Low, and Close prices.
* Calculate daily percentage returns using Open and Close prices.
* Analyze trading volume trends over time.
* Compare closing prices with 20-day and 50-day moving averages.
* Analyze the distribution of daily stock returns using histogram and KDE plots.
* Identify high-volatility days using the ±2 standard deviation method.
* Analyze stock return variation and stability.
* Prepare a financial summary using stock price, return, and trading volume statistics.

## KEY OUTCOMES

* Successfully cleaned the Shopify stock market price and volume attributes.
* Calculated daily percentage returns.
* Visualized OHLC prices over time.
* Analyzed trading volume trends.
* Calculated 20-day and 50-day moving averages.
* Compared closing prices with moving averages.
* Visualized daily return distribution using histogram and KDE plots.
* Calculated mean, variance, and standard deviation of stock returns.
* Identified high-volatility trading days.
* Analyzed stock return variation and stability.
* Generated a financial summary report of stock price, returns, and trading volume.



