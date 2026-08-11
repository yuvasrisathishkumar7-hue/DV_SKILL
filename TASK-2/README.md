<h1 align="center">TASK 2: RETAIL SALES VISUALIZATION, RELATIONSHIP ANALYSIS &amp; BUSINESS INSIGHTS</h1>

<h2>PROJECT OVERVIEW</h2>

<p>
This project focuses on visualizing retail sales and analyzing relationships between sales, profit, discount, and other numerical attributes using Python. Seaborn and Matplotlib are used to create bar plots, box plots, scatter plots, and a correlation heatmap. The analysis helps identify sales patterns, profitability trends, and discount levels that negatively affect profit.
</p>

<h2>OBJECTIVES</h2>

<ul>
  <li>Visualize sales and profit using bar plots and box plots.</li>
  <li>Analyze the relationship between discount and profit.</li>
  <li>Identify discount levels that negatively affect profitability.</li>
  <li>Generate a correlation heatmap for numerical attributes.</li>
  <li>Identify important relationships between sales, profit, discount, and quantity.</li>
  <li>Extract meaningful business insights from the analysis.</li>
  <li>Prepare the findings as a 1-page survey report.</li>
</ul>

<h2>TECHNOLOGIES USED</h2>

<ul>
  <li>Python</li>
  <li>Google Colab</li>
  <li>Pandas</li>
  <li>NumPy</li>
  <li>Matplotlib</li>
  <li>Seaborn</li>
</ul>

<h2>DATASET</h2>

<p><strong>DATASET NAME:</strong> <code>SampleSuperstore.csv</code></p>

<p>The analysis uses important attributes such as:</p>

<ul>
  <li>Sales</li>
  <li>Profit</li>
  <li>Quantity</li>
  <li>Discount</li>
  <li>Category</li>
  <li>Sub-Category</li>
  <li>Shipping Details</li>
</ul>

<h2>PROJECT WORKFLOW</h2>

<h3>STEP 1: IMPORT REQUIRED LIBRARIES</h3>

<p>
Import Pandas, NumPy, Matplotlib, and Seaborn for data analysis and visualization.
</p>

<h3>STEP 2: LOAD THE DATASET</h3>

<p>
Load the cleaned Superstore dataset using Pandas.
</p>

<h3>STEP 3: CREATE BAR PLOTS</h3>

<p>
Create bar plots to compare sales and profit across different product categories.
</p>

<h3>STEP 4: CREATE BOX PLOTS</h3>

<p>
Use box plots to examine the distribution of sales and profit and identify possible outliers.
</p>

<h3>STEP 5: ANALYZE DISCOUNT AND PROFIT</h3>

<p>
Plot discount levels against profit to understand how increasing discounts affect profitability.
</p>

<h3>STEP 6: IDENTIFY DISCOUNT THRESHOLDS</h3>

<p>
Analyze the discount-profit relationship to identify discount levels where profit starts decreasing or becomes negative.
</p>

<h3>STEP 7: GENERATE CORRELATION MATRIX</h3>

<p>
Calculate the correlation between numerical attributes such as:
</p>

<ul>
  <li>Sales</li>
  <li>Profit</li>
  <li>Quantity</li>
  <li>Discount</li>
</ul>

<h3>STEP 8: CREATE CORRELATION HEATMAP</h3>

<p>
Visualize the correlation matrix using a Seaborn heatmap to identify strong positive and negative relationships.
</p>

<h3>STEP 9: IDENTIFY BUSINESS INSIGHTS</h3>

<p>
Interpret the visualizations and correlation results to identify important retail business patterns.
</p>

<h3>STEP 10: PREPARE 1-PAGE SURVEY REPORT</h3>

<p>
Summarize the major findings, relationships, discount impact, and business recommendations in a one-page report.
</p>

<h2>VISUALIZATIONS</h2>

<ul>
  <li>Bar Plot: Sales by Category</li>
  <li>Bar Plot: Profit by Category</li>
  <li>Box Plot: Sales Distribution</li>
  <li>Box Plot: Profit Distribution</li>
  <li>Scatter Plot: Discount vs Profit</li>
  <li>Correlation Heatmap</li>
</ul>

<h2>BUSINESS ANALYSIS</h2>

<h3>Discount vs Profit</h3>

<p>
The relationship between discount and profit is analyzed to determine whether higher discounts improve sales while reducing profit margins.
</p>

<h3>Sales vs Profit</h3>

<p>
Sales and profit are compared to identify whether higher sales always result in higher profitability.
</p>

<h3>Category-wise Performance</h3>

<p>
Different product categories are compared based on their total sales and profit to identify strong and weak-performing categories.
</p>

<h3>Numerical Relationships</h3>

<p>
The correlation heatmap helps identify relationships among sales, profit, quantity, and discount.
</p>

<h2>KEY OUTCOMES</h2>

<ul>
  <li>Visualized category-wise sales and profit.</li>
  <li>Examined sales and profit distributions using box plots.</li>
  <li>Analyzed the relationship between discount and profit.</li>
  <li>Identified discount levels that can negatively affect profitability.</li>
  <li>Generated a correlation heatmap for numerical attributes.</li>
  <li>Identified important relationships between business variables.</li>
  <li>Extracted useful retail business insights.</li>
  <li>Prepared findings in a concise 1-page survey report.</li>
</ul>

<hr>

### VISUALIZATIONS

- Bar Plot: Sales by Category



<img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/88342bd1-7241-4af3-ab0a-0d6168038c54" />



- Bar Plot: Profit by Category


<img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/1b242627-0413-4756-9c2e-179f1d40e1e2" />



- Box Plot: Sales Distribution


<img width="592" height="455" alt="image" src="https://github.com/user-attachments/assets/78fdca83-f55a-43d0-8fae-940983cd621c" />



- Box Plot: Profit Distribution


<img width="592" height="416" alt="image" src="https://github.com/user-attachments/assets/54fab5ba-f47a-4eb2-a5dd-69b07f1c3c1f" />



- Scatter Plot: Discount vs Profit


<img width="592" height="455" alt="image" src="https://github.com/user-attachments/assets/589cb1ab-fec1-4fb0-a27e-4a54b4738e38" />



- Correlation Heatmap


| **Variable Pair**      | **Correlation** | **Relationship**   | **Meaning**                                                           |
| ---------------------- | --------------: | ------------------ | --------------------------------------------------------------------- |
| Sales – Profit         |        **0.48** | Moderate Positive  | Higher sales are generally associated with higher profit.             |
| Sales – Quantity       |        **0.20** | Weak Positive      | Increasing quantity has a limited relationship with sales.            |
| Discount – Profit      |       **-0.22** | Negative           | Higher discounts tend to reduce profit.                               |
| Quantity – Profit      |       **0.056** | Very Weak Positive | Quantity sold has very little relationship with profit.               |
| Discount – Sales       |      **-0.028** | Very Weak Negative | Discount has almost no direct linear relationship with sales.         |
| Delivery Days – Profit |     **-0.0044** | Almost None        | Delivery duration has practically no linear relationship with profit. |


<img width="609" height="518" alt="image" src="https://github.com/user-attachments/assets/f07499c4-1586-4d21-b690-f7d2233433a5" />


| **S.No** | **Graph / Visualization**                    | **Purpose**                                                                         | **What the Graph Shows**                                                                                                      | **Interpretation / Business Insight**                                                                                                                                           |
| -------: | -------------------------------------------- | ----------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|        1 | **Bar Plot: Sales by Category**              | To compare total sales among product categories.                                    | Technology has the highest sales, followed by Furniture and Office Supplies.                                                  | **Technology** is the strongest category in terms of sales and contributes significantly to overall revenue.                                                                    |
|        2 | **Bar Plot: Profit by Category**             | To compare total profit generated by each category.                                 | Technology generates the highest profit, while Furniture generates comparatively lower profit.                                | High sales do not always mean high profit. **Furniture should be analyzed for pricing, costs, and discounts.**                                                                  |
|        3 | **Histogram: Sales Distribution**            | To understand how Sales values are distributed across transactions.                 | Most transactions have relatively low sales values, while a small number have very high sales values.                         | Sales distribution is **right-skewed**, meaning a few high-value orders contribute significantly to total sales.                                                                |
|        4 | **Box Plot: Sales Distribution by Category** | To compare the spread of Sales across categories and identify outliers.             | Sales vary within each category, with several unusually high-value transactions.                                              | The presence of outliers indicates that some orders have exceptionally high sales and may require separate analysis.                                                            |
|        5 | **Box Plot: Profit Distribution**            | To examine the spread of Profit and identify unusually high profits or losses.      | Most profits are concentrated near zero, with many positive and negative outliers.                                            | Some transactions generate significant profits while others generate substantial losses. Loss-making transactions should be investigated.                                       |
|        6 | **Scatter Plot: Discount vs Profit**         | To study the relationship between Discount and Profit.                              | Higher discount levels contain more negative-profit transactions.                                                             | There is a **negative relationship** between Discount and Profit. Excessive discounts can reduce or eliminate profitability.                                                    |
|        7 | **Correlation Heatmap**                      | To measure the strength and direction of relationships between numerical variables. | Sales and Profit have the strongest meaningful positive relationship, while Discount and Profit have a negative relationship. | **Sales–Profit = 0.48** indicates a moderate positive relationship, while **Discount–Profit = -0.22** indicates that higher discounts tend to be associated with lower profits. |


<h1>1-PAGE SURVEY REPORT</h1>

<h2>RETAIL SALES VISUALIZATION, RELATIONSHIP ANALYSIS &amp; BUSINESS INSIGHTS</h2>

<h3>Introduction</h3>

<p>
The Superstore Sales dataset was analyzed to understand retail sales performance, profitability, discount impact, and relationships among numerical variables. Python, Pandas, Matplotlib, and Seaborn were used for data analysis and visualization.
</p>

<h3>Analysis Performed</h3>

<p>
Bar plots were created to compare sales and profit across product categories. Box plots were used to understand the distribution of sales and profit and identify outliers. A scatter plot was used to analyze the relationship between discount and profit. A correlation heatmap was generated to study relationships among numerical attributes such as Sales, Profit, Quantity, and Discount.
</p>

<h3>Key Findings</h3>

<p>
The analysis shows that sales volume and profitability are not always directly related. Higher discounts can increase sales but may reduce profit margins. At higher discount levels, some transactions may result in very low or negative profits. Category-wise analysis also helps identify products that contribute strongly to sales and profitability.
</p>

<h3>Business Insights</h3>

<p>
Businesses should carefully control discount levels instead of providing excessive discounts. Discount strategies should be based on product profitability and customer demand. Categories and products with consistently higher profitability should receive greater attention, while low-profit products should be reviewed for pricing and discount strategies.
</p>

<h3>Conclusion</h3>

<p>
The visualization and relationship analysis provides useful insights into retail performance. The analysis demonstrates how data visualization and correlation analysis can support better pricing, discount, and product management decisions.
</p>

<hr>

<p align="center">
<strong>Retail Sales Visualization &amp; Business Insights</strong>
</p>
