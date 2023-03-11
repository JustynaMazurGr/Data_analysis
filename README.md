# Data_analysis

The task is performed on a file consisting of 1000 rows of data from https://archive.ics.uci.edu/ml/datasets/Adult.
## Task: 
Answer to the question: Does education have an impact on income level?

This code performs data analysis on income and education. 
It loads data from a csv file named "Adult-1000_decission_class_mapped.csv" using the pandas library and then processes the data to create pie charts for two groups:
individuals with income above 50,000 dollars (class >50K) and individuals with income equal to or less than 50,000 dollars (class <=50K).

In the first part of the code, a dictionary is created with keys as education levels and values as the number of individuals in each income category
(class >50K or class <=50K). Then, the dictionary is converted to a pandas DataFrame object.

In the next part of the code, two pie charts are created, one for class >50K and one for class <=50K.
The charts are created using the plot.pie() method from the matplotlib library and are populated with the appropriate data and labels.
Finally, the charts are displayed using the show() function. At the end of the code, the generated DataFrames along with their sums are also displayed.
