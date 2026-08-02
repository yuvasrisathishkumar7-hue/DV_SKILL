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
