# TASK 10: HOUSE PRICE VISUALIZATION, GEOGRAPHIC CLUSTERING & REAL-ESTATE INVESTMENT INSIGHTS

## PROJECT OVERVIEW

This project focuses on analyzing and visualizing the King County House Sales dataset using Python, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn. It examines the relationship between living area and house prices, compares property prices across grades and conditions, analyzes waterfront price differences, explores geographic price patterns, and evaluates property characteristics associated with house price variation.

The project also applies K-Means clustering to identify geographic property groups, compares median house prices across ZIP codes and geographic clusters, and generates a real-estate investment summary report. The analysis provides insights into property valuation patterns and supports data-driven real-estate research.

## OBJECTIVES

- Load and prepare the processed King County House Sales dataset.
- Extract and calculate property-related features, including sale year, property age, renovation status, and price per square foot.
- Analyze the relationship between living area and house price using scatter plots and regression trend lines.
- Identify houses priced above and below the linear regression trend.
- Compare house prices across property grades and conditions.
- Analyze waterfront and non-waterfront property prices.
- Visualize geographic house price distributions using latitude and longitude.
- Identify the top 10 ZIP codes by median house price.
- Analyze property age, renovation status, bedrooms, bathrooms, and price per square foot.
- Generate a correlation heatmap for property characteristics.
- Apply K-Means clustering to identify geographic property groups.
- Compare property prices and characteristics across geographic clusters.
- Compare expensive and less expensive ZIP codes.
- Generate a real-estate investment summary report.
- Identify major factors associated with house price variation and discuss the limitations of the analysis.
- Save the final analysis dataset as a CSV file.

## TECHNOLOGIES USED

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Linear Regression
- K-Means Clustering
- StandardScaler

## DATASET

**Dataset Name:** `kc_house_performance.csv`

The dataset contains property sales information and additional features calculated during the previous analysis task.

### Key Attributes

- ID
- Date
- Price
- Bedrooms
- Bathrooms
- Living Area (`sqft_living`)
- Lot Area (`sqft_lot`)
- Property Grade (`grade`)
- Property Condition (`condition`)
- Year Built (`yr_built`)
- Year Renovated (`yr_renovated`)
- Waterfront Status (`waterfront`)
- Latitude (`lat`)
- Longitude (`long`)
- ZIP Code (`zipcode`)
- Sale Year (`sale_year`)
- Property Age (`property_age`)
- Renovation Status (`is_renovated`)
- Price per Square Foot of Living Area (`price_per_sqft_living`)
- Price per Square Foot of Lot Area (`price_per_sqft_lot`)

## PROJECT WORKFLOW

### STEP 1: IMPORT REQUIRED LIBRARIES AND LOAD THE DATASET

Imported Pandas, NumPy, Matplotlib, and Seaborn for data processing and visualization. Loaded the processed King County House Sales dataset and inspected its first five rows, shape, and column names.

### STEP 2: PREPARE THE PROPERTY DATA

Converted the date column into datetime format and ensured that the required calculated features were available. These features include sale year, property age, renovation status, and price per square foot of living and lot areas.

Removed rows containing missing values in the essential price, living area, latitude, and longitude columns.

### STEP 3: ANALYZE LIVING AREA AND HOUSE PRICE

Created two scatter plots to examine the relationship between living area and house price:

- **Linear Regression Plot:** Displays the linear trend between living area and house price.
- **Nonlinear Trend Plot:** Uses LOWESS smoothing to explore possible nonlinear patterns.

Applied Linear Regression to estimate house prices based on living area. Calculated the difference between actual and predicted prices to identify the 10 houses priced highest above and the 10 priced lowest below the linear trend.

### STEP 4: ANALYZE PROPERTY GRADE AND CONDITION

Created box plots to compare house price distributions across property grades and property conditions.

Calculated and visualized median house prices for each grade and condition category to understand differences in property valuation.

### STEP 5: ANALYZE WATERFRONT PRICE PREMIUM

Created a box plot comparing waterfront and non-waterfront property prices.

Calculated the mean, median, and number of houses in each waterfront category. Estimated the observed average price difference and percentage price premium for waterfront properties when both categories are available.

### STEP 6: ANALYZE GEOGRAPHIC HOUSE PRICES

Created a geographic scatter plot using longitude and latitude, with colors representing house prices.

Grouped properties by ZIP code and calculated:

- Median house price
- Average house price
- Number of houses
- Average property grade
- Average living area

Identified and visualized the top 10 ZIP codes by median house price. Also examined the relationship between property age and house price using a regression plot.

### STEP 7: PERFORM MULTIVARIABLE PROPERTY VALUATION ANALYSIS

Analyzed several property characteristics associated with house price variation:

- Average house price by renovation status
- Average price per square foot by property grade
- Living area versus price per square foot
- Average price per square foot by property condition
- Average house price by number of bedrooms
- Average house price by number of bathrooms

Generated a correlation matrix and heatmap to examine relationships among price, living area, lot area, bedrooms, bathrooms, grade, condition, waterfront status, property age, and price per square foot of living area.

### STEP 8: IDENTIFY GEOGRAPHIC CLUSTERS USING K-MEANS

Applied K-Means clustering to the latitude and longitude coordinates of properties.

Standardized the geographic coordinates using StandardScaler and grouped the properties into five geographic clusters.

Assigned cluster labels to the properties and visualized the geographic groups using a scatter plot.

Compared the clusters using:

- Average house price
- Median house price
- Number of houses
- Average property grade
- Average living area
- Number of waterfront houses

Identified clusters with higher median house prices and examined their property characteristics.

### STEP 9: GENERATE THE REAL-ESTATE INVESTMENT SUMMARY REPORT

Compared the top 10 most expensive ZIP codes with the bottom 10 ZIP codes based on median house prices.

Calculated the average median price, living area, and property grade for both groups. Generated a comparison chart and printed a real-estate summary containing overall prices, living area correlation, property grade, condition, waterfront status, renovation status, property age, ZIP code rankings, and geographic cluster comparisons.

Also documented the limitations of the analysis, including extreme values, geographic clustering choices, differences within ZIP codes, and the inability to establish cause-and-effect relationships from the observed patterns.

### STEP 10: ANALYZE INSIGHTS, DRAW CONCLUSIONS, AND SAVE THE DATASET

Summarized the major factors associated with house price variation, including living area, property grade, property condition, waterfront status, renovation status, property age, and geographic location.

Printed the final conclusions and saved the analysis dataset as `Final Week-10.CSV` for further analysis.

## DATA VISUALIZATIONS

The project includes the following visualizations generated by the code:

1. **Living Area vs House Price** — Scatter Plot with Linear Regression Trend Line


<img width="854" height="556" alt="image" src="https://github.com/user-attachments/assets/69b276fd-1a84-4f3b-9132-be4b5c2141b2" />




2. **Nonlinear Relationship Between Living Area and House Price** — LOWESS Trend Plot



<img width="854" height="556" alt="image" src="https://github.com/user-attachments/assets/01e2adff-9de9-466c-bc11-84adf6a1dd46" />







3. **House Price Distribution by Property Grade** — Box Plot



<img width="996" height="556" alt="image" src="https://github.com/user-attachments/assets/78fd4cc8-10b4-427b-9c0f-e7fbbe275782" />




4. **House Price Distribution by Property Condition** — Box Plot



<img width="841" height="556" alt="image" src="https://github.com/user-attachments/assets/7c3bdac8-b493-4228-96c4-135927949a6c" />



5. **Median House Price by Property Grade** — Bar Chart



<img width="856" height="556" alt="image" src="https://github.com/user-attachments/assets/be619746-f5fb-4bfe-8314-74295d89ada0" />


6. **Median House Price by Property Condition** — Bar Chart


<img width="812" height="479" alt="image" src="https://github.com/user-attachments/assets/e82ef820-9e85-446a-ace7-3e708e38e599" />



7. **Waterfront vs Non-Waterfront House Prices** — Box Plot



<img width="686" height="556" alt="image" src="https://github.com/user-attachments/assets/13c94538-4024-4427-a60f-9aff0b672f66" />



8. **Geographical Distribution of House Prices** — Geographic Scatter Plot



<img width="958" height="710" alt="image" src="https://github.com/user-attachments/assets/dae47778-3175-4b44-9de1-4109fe0416a8" />



9. **Top 10 ZIP Codes by Median House Price** — Horizontal Bar Chart


<img width="880" height="556" alt="image" src="https://github.com/user-attachments/assets/b482f214-c1f1-4b93-908a-248fdb0a91bf" />




10. **Property Age vs House Price** — Regression Plot


<img width="851" height="556" alt="image" src="https://github.com/user-attachments/assets/8c5e2c0c-34aa-4c4d-ac3b-c40a9983211b" />



11. **Average House Price by Renovation Status** — Bar Chart




<img width="734" height="479" alt="image" src="https://github.com/user-attachments/assets/3fa68af8-de8e-4811-ac47-3c8f1de77be8" />


12. **Average Price per Square Foot by Property Grade** — Bar Chart



<img width="860" height="556" alt="image" src="https://github.com/user-attachments/assets/caec97ad-a331-475e-8479-7453efaad526" />



13. **Living Area vs Price per Square Foot** — Scatter Plot


<img width="874" height="556" alt="image" src="https://github.com/user-attachments/assets/c8d7753e-5f7b-4c41-ae2b-b21d0abd3a49" />


14. **Average Price per Square Foot by Property Condition** — Bar Chart


<img width="783" height="479" alt="image" src="https://github.com/user-attachments/assets/04489116-d857-495d-a574-173f05056a52" />



15. **Average House Price by Number of Bedrooms** — Bar Chart


<img width="856" height="479" alt="image" src="https://github.com/user-attachments/assets/418e6f34-afe8-4ad4-b1e0-9a51d5baf372" />


16. **Average House Price by Number of Bathrooms** — Bar Chart


<img width="996" height="498" alt="image" src="https://github.com/user-attachments/assets/a159a7bf-6399-4a3d-ab7b-6ec104676dac" />



17. **Correlation Heatmap of Property Characteristics** — Heatmap


<img width="1061" height="828" alt="image" src="https://github.com/user-attachments/assets/93d17f78-8387-4815-bd3b-e277ff404d7f" />


18. **Geographic Clusters of King County Properties** — Cluster Scatter Plot


<img width="972" height="710" alt="image" src="https://github.com/user-attachments/assets/80e40344-378d-4e77-b6c9-ef1b47e27d26" />




19. **Median House Price by Geographic Cluster** — Bar Chart


<img width="889" height="556" alt="image" src="https://github.com/user-attachments/assets/77ea1716-03e3-4043-8344-da2136393c4c" />



20. **Comparison of Expensive and Less Expensive ZIP Codes** — Bar Chart

<img width="889" height="533" alt="image" src="https://github.com/user-attachments/assets/6bd25887-f5b9-440b-895f-e4d4d71b7cce" />


## KEY ANALYSIS

- Examined linear and nonlinear relationships between living area and house price.
- Identified properties whose actual prices differed considerably from the linear regression predictions.
- Compared property price distributions across grades and conditions.
- Calculated observed average price differences between waterfront and non-waterfront properties.
- Identified ZIP codes with the highest median house prices.
- Examined property age and renovation status in relation to house prices.
- Compared average house prices and price per square foot across property characteristics.
- Generated a correlation heatmap to explore relationships among numerical variables.
- Applied K-Means clustering to group properties by geographic coordinates.
- Compared property values and characteristics across geographic clusters.
- Prepared a comparative analysis of expensive and less expensive ZIP codes.
- Generated a real-estate investment summary and documented analytical limitations.

## REAL-ESTATE INVESTMENT INSIGHTS

- **Living Area:** Regression plots and correlation analysis help examine how living area is associated with house prices.
- **Property Grade:** Comparing median prices across grades helps investigate differences in property valuation.
- **Property Condition:** Price distributions and median values reveal variations among condition categories.
- **Waterfront Access:** Comparing waterfront and non-waterfront properties helps estimate the observed price difference associated with waterfront status.
- **Geographic Location:** ZIP code analysis and geographic clustering help identify areas with different property price distributions.
- **Property Age:** Regression and correlation analysis help explore the relationship between property age and house price.
- **Renovation Status:** Comparing average and median prices helps examine price differences between renovated and non-renovated properties.
- **Property Size:** Price-per-square-foot analysis provides another perspective on property valuation.
- **Bedrooms and Bathrooms:** Grouped price comparisons help examine how house prices vary with room counts.
- **Geographic Clusters:** Comparing median prices, property grades, living areas, and waterfront counts helps characterize the identified property groups.

These findings represent observed relationships in the dataset. They do not independently establish causation or guarantee future property performance.

## REAL-ESTATE INVESTMENT RECOMMENDATIONS

### 1. COMPARE PROPERTY VALUES WITHIN LOCATIONS

Examine median house prices and property characteristics across ZIP codes before comparing potential investment locations.

### 2. EVALUATE PROPERTY QUALITY

Consider property grade, condition, living area, and other structural characteristics when comparing similar properties.

### 3. ASSESS LOCATION-RELATED FEATURES

Investigate geographic price patterns, waterfront access, and neighborhood differences before evaluating property values.

### 4. CONSIDER RENOVATION REQUIREMENTS

Compare renovation status, property age, and condition to understand potential maintenance and improvement requirements.

### 5. USE PRICE PER SQUARE FOOT CAREFULLY

Compare properties with similar sizes and locations. Living area and lot area are different measurements and should not be treated as interchangeable.

### 6. INVESTIGATE UNUSUAL PRICE DIFFERENCES

Review properties priced substantially above or below regression predictions to identify characteristics that may explain their differences.

### 7. COMBINE MULTIPLE PROPERTY CHARACTERISTICS

Evaluate grade, condition, size, location, age, and waterfront status together instead of relying on a single variable.

### 8. CONDUCT FURTHER MARKET RESEARCH

Use current market information, property inspections, comparable sales, expenses, and investment objectives before making financial decisions.

## EXECUTIVE SUMMARY

This project applies data analysis, statistical visualization, regression analysis, correlation analysis, and K-Means clustering to investigate house price variation in King County.

The analysis examines living area, property grade, condition, waterfront access, renovation status, property age, and geographic location. It also compares ZIP codes, identifies geographic property clusters, and summarizes differences in property prices and characteristics.

The resulting charts, statistical summaries, and cluster comparisons help explore property valuation patterns. The project demonstrates how Python-based analytics can support real-estate research while recognizing that observed relationships alone are insufficient for making investment decisions.

## KEY OUTCOMES

- Successfully loaded and prepared the processed King County House Sales dataset.
- Examined living area and house price relationships using linear and nonlinear trend plots.
- Identified properties priced highest above and lowest below the linear regression trend.
- Compared house prices by property grade and condition.
- Calculated the observed waterfront price difference and premium.
- Visualized geographic house price distributions.
- Identified the top 10 ZIP codes by median house price.
- Analyzed renovation status, property age, bedrooms, bathrooms, and price per square foot.
- Generated a correlation heatmap for property characteristics.
- Applied K-Means clustering to geographic coordinates and identified five clusters.
- Compared median prices and property characteristics across geographic clusters.
- Compared expensive and less expensive ZIP codes.
- Generated a real-estate investment summary report.
- Documented the limitations of the analysis.
- Saved the final analysis dataset as `Final Week-10.CSV`.

## CONCLUSION

The project demonstrates how data visualization, regression analysis, correlation analysis, and geographic clustering can be used to explore house price variation. The analysis compares properties by living area, grade, condition, waterfront access, renovation status, property age, and location.

Geographic analysis and ZIP code comparisons provide additional perspectives on differences in property valuation, while K-Means clustering helps group properties according to their coordinates. Together, these techniques provide a structured approach to exploring real-estate data.

The findings can support further property research and valuation studies. However, the results describe patterns in the available dataset and should not be interpreted as proof of causation or as standalone investment advice. Further research using current market data, property-level assessments, and financial considerations is necessary before making real-estate investment decisions.
