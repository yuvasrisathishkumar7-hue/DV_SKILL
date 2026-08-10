## WEEK 1: SUPERSTORE SALES DATA UNDERSTANDING, CLEANING & EXPLORATORY ANALYSIS

### DESCRIPTION

This task focuses on understanding, cleaning, and analyzing the Superstore Sales dataset using Python and Pandas.

### OBJECTIVES

- Load the dataset using Pandas.
- Inspect the dataset using `head()`, `info()`, and `describe()`.
- Convert Order Date and Ship Date columns into proper datetime format.
- Clean and standardize categorical attributes such as Category, Sub-Category, and Segment.
- Calculate initial summary statistics for numerical attributes.

### WORKFLOW

```mermaid
flowchart TD
    A[LOAD DATASET] --> B[DATA INSPECTION]
    B --> C[DATE FORMAT CONVERSION]
    C --> D[CATEGORICAL DATA CLEANING]
    D --> E[SUMMARY STATISTICS CALCULATION]
    E --> F[EXPLORATORY DATA ANALYSIS]
    F --> G[INSIGHTS GENERATION]


<h2>WEEK 2: RETAIL SALES VISUALIZATION, RELATIONSHIP ANALYSIS &amp; BUSINESS INSIGHTS</h2>

<h3>DESCRIPTION</h3>

<p>
This task focuses on visualizing retail sales and analyzing relationships between Sales, Profit, Discount, Quantity, and other numerical attributes using Python, Matplotlib, and Seaborn.
</p>

<h3>OBJECTIVES</h3>

<ul>
  <li>Create bar plots and box plots to visualize sales and profit.</li>
  <li>Analyze the relationship between Discount and Profit.</li>
  <li>Identify discount levels that negatively affect profitability.</li>
  <li>Generate a correlation heatmap for numerical attributes.</li>
  <li>Analyze relationships between Sales, Profit, Discount, and Quantity.</li>
  <li>Generate meaningful business insights from the visualizations.</li>
  <li>Prepare the findings as a 1-page survey report.</li>
</ul>

<h3>WORKFLOW</h3>

```mermaid
flowchart TD
    A[LOAD CLEANED DATASET] --> B[CREATE BAR PLOTS]
    B --> C[CREATE BOX PLOTS]
    C --> D[ANALYZE DISCOUNT VS PROFIT]
    D --> E[GENERATE CORRELATION MATRIX]
    E --> F[CREATE CORRELATION HEATMAP]
    F --> G[IDENTIFY BUSINESS INSIGHTS]
    G --> H[PREPARE 1-PAGE SURVEY REPORT]
```
