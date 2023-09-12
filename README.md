# Getting Started

1. Clone or download this repository to your local machine.
2. Ensure you have Jupyter Notebook installed. If not, you can install it using Anaconda or pip.
3. Open the Jupyter Notebook file (`Descriptive_Statistical_Analysis.ipynb`) in your Jupyter Notebook environment.
4. Execute the code cells step by step to replicate the analysis or modify it for your specific dataset.
5. import dataset

## Requirements 


```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from scipy import stats
import statsmodels.api as sm

 Jupyter Notebook - Descriptive Statistical Analysis

## Introduction

This Jupyter Notebook contains a comprehensive descriptive statistical analysis of a dataset.
Descriptive statistics are an integral part of the Exploratory Data Analysis (EDA) process, helping data analysts to compare variables, understand data distribution, identify outliers, and perform calculations for making predictions.

<details>
<summary style="color: blue;"><b>Review: How do we use statistics as a Data Analyst?</b></summary>

1. <span style="color: green;">**Compare Variables:**</span> Statistics help us compare different variables or data points to gain valuable insights.
2. <span style="color: green;">**Understand Data Distribution:**</span> They allow us to visualize the position and distribution of data points.
3. <span style="color: green;">**Identify Outliers:**</span> Statistics help identify outliers and assess their impact on the data.
4. <span style="color: green;">**Perform Further Calculations:**</span> We can perform various calculations and make predictions using statistical techniques.
</details>

<details>
<summary style="color: blue;"><b>What can we do with statistics?</b></summary>

In this analysis, we'll leverage statistics to perform the following tasks:

1. <span style="color: green;">**Find the Range:**</span> Calculating the range, which is the difference between the highest and lowest values in the dataset (e.g., Range = Highest - Lowest).
2. <span style="color: green;">**Calculate Variance:**</span> Understanding variance as the squared standard deviation, representing the typical distance of a data point from the mean.
3. <span style="color: green;">**Compute Mean:**</span> Finding the mean by summing all dataset values and dividing by the number of data points.
4. <span style="color: green;">**Determine Median:**</span> Identifying the median, which is the middle value of the dataset.
5. <span style="color: green;">**Calculate Percentiles:**</span> Finding the percentile rank of a specific data point.
6. <span style="color: green;">**Divide Data into Quartiles:**</span> Splitting the data into quartile ranges for a deeper understanding.
7. <span style="color: green;">**Calculate Standard Deviation:**</span> Determining the standard deviation as a measure of data dispersion.
</details>

#### Conclusions:

