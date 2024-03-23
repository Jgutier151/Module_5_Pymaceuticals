# Clinical Study Data Analysis Project

# Introduction

For this project, I was tasked with generating all tables and figures needed for the technical report of a clinical study, as well as providing a top-level summary of the study results. The project involved several tasks encompassing data preparation, statistical analysis, visualization, and regression modeling.

# Tasks Overview

# Task 1: Prepare the Data
Merged the provided mouse_metadata and study_results DataFrames into a single DataFrame.
Displayed the number of unique mice IDs and checked for any mouse IDs with duplicate time points.
Created a cleaned DataFrame without duplicate mouse data.
# Task 2: Generate Summary Statistics
Calculated summary statistics for each drug regimen, including mean, median, variance, standard deviation, and SEM of the tumor volume.
Created a DataFrame of summary statistics with drug regimens as index and calculated metrics as columns.
# Task 3: Create Bar Charts and Pie Charts
Generated bar charts to visualize the total number of timepoints for each drug regimen and pie charts to illustrate the distribution of female versus male mice in the study.
# Task 4: Calculate Quartiles, Find Outliers, and Create a Box Plot
Calculated the final tumor volume of each mouse across selected treatment regimens.
Identified potential outliers and created a box plot to visualize the distribution of final tumor volume for all mice in each treatment group.
# Task 5: Create a Line Plot and a Scatter Plot
Generated a line plot to visualize tumor volume versus time point for a single mouse treated with Capomulin.
Created a scatter plot to display average tumor volume versus mouse weight for the Capomulin regimen.
# Task 6: Calculate Correlation and Regression
Calculated the correlation coefficient and performed linear regression modeling between mouse weight and average observed tumor volume for the Capomulin treatment regimen.
Plotted the linear regression model on top of the scatter plot.
Requirements and Evaluation
The project was evaluated based on specific requirements and criteria detailed below each task. Each task contributed to the overall analysis and interpretation of the clinical study data.

# Tools and Techniques Used
Python: Programming language used for data manipulation, analysis, and visualization.  
Pandas: Data manipulation and analysis library in Python.  
Matplotlib: Visualization library for creating plots and charts.  
SciPy: Scientific computing library for statistical analysis.  

# Conclusion
This project involved a comprehensive analysis of clinical study data, including data preparation, statistical analysis, and visualization. By following the outlined tasks, I successfully generated all necessary tables and figures for the technical report and provided insightful summaries of the study results.
