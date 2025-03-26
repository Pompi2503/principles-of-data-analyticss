# Iris Dataset Analysis

## Overview
The tasks assigned explores the famous Iris dataset using Python's sklearn.datasets module. The analysis includes data exploration, statistical summarization, visualization, correlation analysis, and simple linear regression modeling.

## Installation and Set-up

### Prerequisites
Ensure you have the following installed:  
Python 3.x  
Jupyter Notebook  
Required libraries: numpy, pandas, matplotlib, seaborn, sklearn  

### Installation
To install the necessary dependencies, run:  
pip install numpy pandas matplotlib seaborn scikit-learn  

### Usage
To run the analysis, open Jupyter Notebook and execute the notebook containing the implementation.  
task.ipynb  

### Tasks Overview

#### Task 1: Source the Data Set
 •	Import the Iris dataset from sklearn.datasets.  
 •	The load_iris() function returns a dictionary-like object that contains data attributes, target labels, feature names, and a 
    description of the dataset. The dataset includes 150 samples of iris flowers with four features: sepal length, sepal width, petal length, and petal width.  

#### Task 2: Explore the Data Structure
- Print and explain the dataset shape, which shows the number of samples and features.  
- Display the first and last five rows of the dataset to get an overview of the data distribution.  
- List the feature names to understand what measurements are included.  
- Identify the target classes, which correspond to three species of iris flowers: Setosa, Versicolor, and Virginica.  

#### Task3: Summarize the Data
Calculate key statistical metrics for each feature. These statistics help understand the distribution of each feature across different species.
- Mean: Average value of each feature.  
- Minimum: Smallest observed value.  
- Maximum: Largest observed value.  
- Standard Deviation: Measure of feature variation.  
- Median: Middle value when sorted.  

#### Task4: Visualise Features
Create histograms for each feature using matplotlib.  
- Histograms provide insights into the frequency distribution of each feature and help detect skewness or anomalies.  
- Titles and axis labels is added to improve readability.  







