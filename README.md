# Task12-NumPy-Aggregations-and-Statistics
Objective
Use NumPy to calculate summary statistics and understand numerical data.
Tools Used
Python
NumPy
Jupyter Notebook
Functions Covered
This task demonstrates the following NumPy aggregation and statistical functions:
np.sum() -- Calculates the total of the values.
np.mean() -- Calculates the average.
np.median() -- Finds the middle value.
np.min() -- Finds the smallest value.
np.max() -- Finds the largest value.
np.std() -- Calculates standard deviation.
np.var() -- Calculates variance.
np.percentile() -- Calculates a selected percentile.
Example Dataset
import numpy as np

data = np.array([
    [80, 75, 90],
    [85, 88, 92],
    [70, 80, 78],
    [90, 95, 85]
])
Statistical Analysis
print("Sum:", np.sum(data))
print("Mean:", np.mean(data))
print("Median:", np.median(data))
print("Minimum:", np.min(data))
print("Maximum:", np.max(data))
print("Standard Deviation:", np.std(data))
print("Variance:", np.var(data))
print("25th Percentile:", np.percentile(data, 25))

# Column-wise and row-wise calculations
print("Column means:", np.mean(data, axis=0))
print("Row means:", np.mean(data, axis=1))
Understanding Axis
axis=0: Performs the calculation column-wise.
axis=1: Performs the calculation row-wise.
No axis: Performs the calculation on all elements.
Result / Interpretation
The NumPy functions summarize the dataset by showing its total, average, middle value, range, and spread. The axis parameter helps compare values across columns or rows.
Conclusion
This task provided practical experience with NumPy aggregation and statistical functions for basic numerical data analysis.
