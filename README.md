# Data Analysis Course Overview

## Course Content:
- Completed a comprehensive data analysis course covering projects on rainfall prediction, tumor detection, and COVID-19 analysis.
- Tasks included feature scaling, label encoding, and building classification models.
- Miscellaneous topics were covered to enhance proficiency in data analysis techniques.

## Rainfall Prediction:
- **Code Description:** Analyzes rainfall prediction using linear regression.
- Reads weather data from a CSV file, processes it by dropping unnecessary columns, replaces 'T' and '-' values, and saves the cleaned data to a new CSV file.
- Utilizes linear regression to analyze precipitation trends over time, visualizing the data with scatter plots.
- Isolates specific attributes for further analysis.

## Tumor Detection:
- **Code Description:** Analyzes tumor detection data using pandas, numpy, matplotlib, and seaborn libraries.
- Reads a CSV file containing tumor data, explores the dataset's structure and statistics, visualizes correlations between features using heatmaps.
- Preprocesses the data by mapping the diagnosis column to binary values.
- Displays the first few rows of the modified dataset.

## COVID-19 Analysis:
- **Code Description:** Imports and preprocesses COVID-19 infection data, aggregates it by country, then joins it with a happiness report dataset.
- Computes correlation matrices and visualizes relationships between GDP per capita, social support, healthy life expectancy, freedom to make life choices, and COVID-19 infection rates.

## Feature Scaling, Label Encoding, Classification Model, Neural Networks:
- **Code Segment Description:** Performs feature scaling using Min-Max Scaling and Standardization.
  - Min-Max Scaling: Scales the features to a specified range, typically between 0 and 1.
  - Standardization: Scales the features such that they have a mean of 0 and a standard deviation of 1.
- Applies both scaling techniques to the "Age" and "EstimatedSalary" columns of the dataset.
- Uses a Support Vector Machine (SVM) for classification, predicting customer churn based on features like age and salary.
- Employs a neural network for the same task.
- Prints accuracy scores for different scaling methods to evaluate performance.
