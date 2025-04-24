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
tasks.ipynb  

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

### Task 7: Analyse Class Distribution  
 - To analyse the distribution of petal lengths across three species in the Iris dataset.  
 - Present median, interquartile range and outlier in the dataset.  
 - Present data in visual and interpretable format using box plots  

 ### Task8: Compute Correlations
 - The purpose of this to perform exploratory analysis by visualising pairwise relationship/  
 - A corrleation matrix is used and heatmapt is used to depict pairwise relationship.  
 - We can see how variables are related poritively or negatively.  


## Task9: To fit a Linear Regression Line
- This is perform for predictive analysis between twpo variables of the iris dataset.  
- by Calculating coeffecient fo determiantion R^2, we will determine how much variance in the petal length is determined by the independent variable.  

### Task10: Task 10: Too Many Features
- In this task, we will be using Seaborn to perform an exploratory analysis of variables in Iris dataset and how they vary for 
  different target class (species).  
- We are using Pairplot chart from seaborn library to depict relationship between different features in the class. Pairplot will 
  show histogram for each feature as in petal lenght, width etc to depict if the data shows normal distribution, or it is skewed or outlier.  
- It shows scatter plot when we are analyzing diffrent features as petal lenght vs width or sepal width vs lenght. It also shows 
  different points in the plot to identify which target class (species), they belong to.  
- For Iris datset, with 4 features, pairplot will show 16 plots based on (4*4).  

