## 1. Data Cleaning and Transformation

### Exercise: Handling Missing Values and Creating New Columns

**Objective:** Clean the car dataset by handling missing values and create a new column based on existing data.

**Task:**
1. Load the car dataset from 'data.csv'.
2. Check for missing values in the 'Weight' column and fill them with the mean weight.
3. Create a new column called 'Efficiency' which is the ratio of CO2 to Volume.
4. Filter the dataset to show only cars with a Volume greater than 1500 and Efficiency less than 0.07.

## 2. Data Aggregation and Grouping

### Exercise: Analyzing Car Data by Brand

**Objective:** Use grouping and aggregation functions to analyze the car dataset.

**Task:**
1. Group the data by 'Car' (brand) and calculate the mean 'CO2' emissions for each brand.
2. Find the car brand with the highest average 'Weight'.
3. Create a pivot table with 'Car' as the index, 'Model' as the columns, and 'CO2' as the values. Fill missing values with 0.

## 3. Time Series Analysis

### Exercise: Analyzing Daily Sales Data

**Objective:** Create and analyze a time series dataset of daily sales.

**Task:**
1. Create a date range for the year 2023 and generate random sales data.
2. Resample the data to show monthly total sales.
3. Calculate a 7-day rolling average of sales.
4. Find the month with the highest total sales.

Citations:
[2] https://www.w3resource.com/python-exercises/pandas/index.php
[3] https://pynative.com/python-pandas-exercise/
[4] https://favtutor.com/blogs/pandas-exercises-python
[5] https://github.com/guipsamora/pandas_exercises
[6] https://github.com/shreymukh/Pandas-Challenge
[7] https://pages.stat.wisc.edu/~kdlevin/teaching/Fall2019/STATS507/hw/homework6.pdf
[8] https://codesolid.github.io/solutions/PandasExercises.html
[9] https://github.com/Flonks/Assignment-1/blob/main/Pandas%20and%20python%20practice.ipynb