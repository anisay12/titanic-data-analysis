# Titanic Data Analysis

## Overview
This project performs a comprehensive analysis of the Titanic dataset. The analysis includes exploratory data analysis (EDA), data visualization, statistical summaries, and insights into passenger survival rates. The code utilizes various Python libraries such as pandas, numpy, seaborn, and matplotlib to perform these tasks.

## Installation

To run the analysis, you need to have the following Python libraries installed:

- numpy
- pandas
- seaborn
- pandas-profiling
- matplotlib

You can install these dependencies using pip:

```bash
pip install numpy pandas seaborn pandas-profiling matplotlib
```

## Dataset

The dataset used for this analysis is the Titanic dataset, which is available at the following URL:

```
https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv
```

## Analysis Steps

### 1. Load the Dataset
The dataset is loaded into a pandas DataFrame for analysis.

### 2. Data Dimensions
Determine the number of rows and columns in the dataset.

### 3. Exploratory Data Analysis (EDA)
- Generate a comprehensive profiling report using pandas-profiling.
- Visualize distributions of variables using histograms and box plots.
- Identify missing values in the dataset.

### 4. Statistical Summaries
- Calculate descriptive statistics (mean, median, variance, standard deviation) for numerical variables.
- Determine the proportion of survivors among passengers.

### 5. Data Visualization
- Plot histograms and box plots to understand the distribution of key variables.
- Visualize survival rates based on various passenger attributes (e.g., age, sex, class).

### 6. Transformation and Cleaning
- Create a new DataFrame (`titanic_numeric`) with numerical representations of categorical variables.
- Handle missing values and transform variables as necessary.

### 7. Specific Analyses
- Determine the mean age of passengers.
- Identify the highest fare paid.
- Analyze the distribution of passengers based on their embarkation point.
- Extract and analyze subsets of data (e.g., passengers who embarked from Cherbourg).

### 8. Survival Analysis
- Compare survival rates between different groups (e.g., men vs. women, different classes).
- Visualize survival rates using pie charts and bar plots.

### 9. Sorting and Filtering
- Sort passengers by age to identify the oldest passenger and their embarkation point.
- Examine if survivors paid higher fares compared to those who did not survive.

### 10. Class-wise Survival Proportions
- Calculate and compare the survival proportions of male passengers across different classes.

## How to Run

1. Ensure all dependencies are installed.
2. Download the dataset from the provided URL.
3. Run the analysis script.

## Conclusion

The analysis provides detailed insights into the Titanic dataset, highlighting key factors that influenced passenger survival rates. The visualizations and statistical summaries help in understanding the characteristics of the passengers and the impact of different variables on survival.
