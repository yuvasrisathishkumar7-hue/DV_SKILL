# TASK 7: STUDENT PERFORMANCE VISUALIZATION, SCORE RELATIONSHIP & EDUCATIONAL EQUITY INSIGHTS

## PROJECT OVERVIEW

This project focuses on analyzing and visualizing student performance data using Python, Pandas, Matplotlib, and Seaborn. It examines average test scores across parental education levels and lunch types, compares Math score distributions based on test preparation, and explores relationships between Math, Reading, and Writing scores.

The project also highlights potential educational performance gaps and provides recommendations to improve educational equity and access to learning resources.

## OBJECTIVES

- Load and prepare the student performance dataset.
- Compare average test scores across parental education levels and lunch types.
- Create a grouped bar chart for average Math, Reading, and Writing scores.
- Analyze Math score variance based on test preparation.
- Visualize relationships between Math, Reading, and Writing scores using scatter plots.
- Generate a correlation matrix for the three subjects.
- Create a correlation heatmap.
- Identify potential educational equity gaps.
- Provide educational policy recommendations.

## TECHNOLOGIES USED

- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn

## DATASET

**Dataset Name:** `Studentperformance_preprecessed.csv`

The dataset contains student demographic information, parental education, lunch type, test preparation status, and academic scores.

### Key Attributes

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch
- Test Preparation Course
- Math Score
- Reading Score
- Writing Score
- Total Marks
- Percentage

## PROJECT WORKFLOW

### STEP 1: IMPORT REQUIRED LIBRARIES

Imported Pandas for data manipulation, Matplotlib for plotting, and Seaborn for statistical visualization.

### STEP 2: LOAD THE DATASET

Loaded the preprocessed student performance dataset into a Pandas DataFrame using `read_csv()`.

### STEP 3: PREPARE STUDENT PERFORMANCE DATA

Selected the relevant attributes for analyzing parental education, lunch type, test preparation, and subject-wise scores.

### STEP 4: CREATE A GROUPED BAR CHART

Calculated the average Math, Reading, and Writing scores for combinations of parental education levels and lunch types. Displayed the results using a grouped bar chart.

### STEP 5: CREATE A BOX PLOT

Used a box plot to compare Math score distributions between students who completed test preparation and those who did not.

### STEP 6: CREATE SCATTER PLOTS

Created three scatter plots to visualize subject-wise score relationships:

- Math vs Reading
- Math vs Writing
- Reading vs Writing

### STEP 7: GENERATE A CORRELATION MATRIX

Calculated the correlation coefficients among Math, Reading, and Writing scores using Pandas.

### STEP 8: CREATE A CORRELATION HEATMAP

Used Seaborn to visualize the correlation matrix, making it easier to identify the strength and direction of relationships between subjects.

### STEP 9: ANALYZE EDUCATIONAL EQUITY

Examined differences in academic performance across parental education levels, lunch types, and test preparation groups to identify potential areas requiring additional educational support.

### STEP 10: PREPARE EDUCATIONAL POLICY RECOMMENDATIONS

Developed recommendations focused on equal learning opportunities, academic support, accessible test preparation, nutrition, and continuous performance monitoring.

## DATA VISUALIZATIONS

1. **Average Test Scores by Parental Education and Lunch Type** — Grouped Bar Chart
2. **Math Score Variance by Test Preparation** — Box Plot
3. **Math vs Reading Scores** — Scatter Plot
4. **Math vs Writing Scores** — Scatter Plot
5. **Reading vs Writing Scores** — Scatter Plot
6. **Correlation Heatmap of Test Scores** — Heatmap

## KEY ANALYSIS

- Compared average subject scores across parental education levels and lunch types.
- Examined the distribution and variability of Math scores by test preparation status.
- Visualized the relationships between Math, Reading, and Writing scores.
- Calculated correlation coefficients to measure relationships between subjects.
- Explored potential differences in academic performance across student groups.
- Identified areas where additional educational support may be beneficial.

## EDUCATIONAL EQUITY INSIGHTS

- Parental education levels may be associated with differences in average student performance.
- Lunch categories may provide insight into differences in students' access to resources, although lunch type alone does not establish a student's socioeconomic status.
- Test preparation may be associated with differences in academic performance.
- Relationships among Math, Reading, and Writing scores can help educators understand patterns in subject-wise achievement.
- Students who experience academic difficulties may benefit from additional learning support and mentoring.

These insights should be interpreted as patterns in the dataset rather than proof of direct cause-and-effect relationships.

## EDUCATIONAL POLICY RECOMMENDATIONS

### 1. PROVIDE FREE ACADEMIC SUPPORT

Offer additional classes, tutoring, and learning materials to students who require academic assistance.

### 2. IMPROVE ACCESS TO TEST PREPARATION

Provide accessible test preparation programs to all students, regardless of their financial background.

### 3. PROVIDE NUTRITIONAL SUPPORT

Ensure access to nutritious meals to support student well-being and learning.

### 4. SUPPORT STUDENTS REQUIRING ADDITIONAL HELP

Introduce mentoring, counselling, and individualized learning plans where appropriate.

### 5. ENSURE EQUAL ACCESS TO LEARNING RESOURCES

Improve access to textbooks, computers, internet facilities, and digital learning materials.

### 6. MONITOR STUDENT PERFORMANCE

Regularly analyze academic performance to identify achievement gaps and provide timely support.

## EXECUTIVE SUMMARY

This project applies data visualization and correlation analysis to understand student performance patterns. It compares average scores across parental education and lunch categories, examines Math score distributions by test preparation status, and visualizes relationships among Math, Reading, and Writing scores.

The findings can help educators explore potential performance gaps and plan appropriate academic support. The project emphasizes equal learning opportunities and evidence-based educational decisions.

## KEY OUTCOMES

- Successfully loaded the preprocessed student performance dataset.
- Compared average Math, Reading, and Writing scores across parental education and lunch categories.
- Created a grouped bar chart for average score comparison.
- Created a box plot to examine Math score distributions by test preparation.
- Generated three scatter plots for subject-wise score relationships.
- Calculated a correlation matrix for Math, Reading, and Writing scores.
- Created a correlation heatmap.
- Explored potential educational equity factors.
- Prepared educational policy recommendations.

## CONCLUSION

The project demonstrates how Python-based data analysis and visualization can be used to explore student academic performance. Grouped bar charts, box plots, scatter plots, and correlation heatmaps provide different perspectives on score distributions and relationships.

The analysis can support educators in identifying areas for improvement and developing inclusive learning strategies. Further investigation using additional student background information would help provide a more comprehensive understanding of educational equity.
