# Iris Dataset Analysis

## Overview
The tasks revolves around Iris dataset, which is very popular dataset for machine learning and pattern recognition.I have used python sklearn module to explore this data. other python libraries like numpy and matplotlib and panda dataframework is used to present data in a more readable format, suitable for data analysis. The analysis in these tasks involbe data exploration, statistical summarization, visualisation, correlation analysis, and linear regression modelling.


## Installation and Set-up

### Prerequisites
Ensure you have the following installed:  
Python 3.11
Jupyter Notebook  
Required libraries: numpy, pandas, matplotlib, seaborn, sklearn  

### Installation
To install the necessary dependencies, run:  
pip install numpy pandas matplotlib seaborn scikit-learn  

### Usage
To run the analysis, open Jupyter Notebook and execute the notebook containing the implementation.  
task.ipynb  

## Tasks Overview

### Task 1: Source the Data Set
 •	Import the Iris dataset from sklearn.datasets.  
 •	The load_iris() function returns a dictionary-like object that contains data attributes, target labels, feature names, and a 
    description of the dataset. The dataset includes 150 samples of iris flowers with four features: sepal length, sepal width, petal length, and petal width.  

### Task 2: Explore the Data Structure
- Print and explain the dataset shape, which shows the number of samples and features.  
- Display the first and last five rows of the dataset to get an overview of the data distribution.  
- List the feature names to understand what measurements are included.  
- Identify the target classes, which correspond to three species of iris flowers: Setosa, Versicolor, and Virginica.  

### Task3: Summarize the Data
Calculate key statistical metrics for each feature. These statistics help understand the distribution of each feature across different species.
- Mean: Average value of each feature.  
- Minimum: Smallest observed value.  
- Maximum: Largest observed value.  
- Standard Deviation: Measure of feature variation.  
- Median: Middle value when sorted.  

### Task 4: Visualise Features
Create histograms for each feature using matplotlib.  
- Histograms provide insights into the frequency distribution of each feature and help detect skewness or anomalies.  
- Titles and axis labels is added to improve readability.  

### Task 5: Investigate Relationship
- Select two features and create a scatter plot to analyze their relationship.
- Color-code the points based on species to visually separate the three classes.
- This visualization helps in identifying clusters or patterns among different iris species.

### Task 6: Analyze Relationship
- Use numpy.polyfit to compute and overlay a regression line on the scatter plot from Task 5.
- This line represents the best linear approximation of the relationship between the two features.



