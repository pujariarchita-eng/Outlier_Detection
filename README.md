# Outlier Detection Using a Box Plot

## Objective
To create a box plot for a numerical variable and identify potential outliers in a dataset.

## Tools Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Dataset
A sample Employee Salary dataset was created using Python. It contains employee IDs and salary values.

## Methodology
1. Create and display the dataset.
2. Calculate the first quartile (Q1) and third quartile (Q3).
3. Calculate the Interquartile Range (IQR).
4. Determine the lower and upper bounds.
5. Identify potential outliers.
6. Visualize the salary distribution using a box plot.
7. Interpret the results.

## Formula
IQR = Q3 - Q1

Lower Bound = Q1 - 1.5 × IQR

Upper Bound = Q3 + 1.5 × IQR

## Result
The box plot and IQR method help identify unusually high or low salary values. The sample dataset includes an unusually high salary of ₹2,00,000, which is expected to be flagged as a potential outlier.

## Conclusion
The task demonstrates how statistical analysis and data visualization can be used for basic outlier detection. Potential outliers should be investigated before making decisions about removing or modifying them.

## Author
AI-ML Task – Outlier Detection
