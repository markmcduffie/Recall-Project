# Recall-Project
CSE6242 Team 071 Project Code Files

## Description
The python package conatianing the majority of our project code is project_0_5. Our code steps through the process of how we built our various models for automobile stock price estimation in the event of a recall. The statistical analysis used for obtaining our recall indicator values that we used in the regression models can be found in the recall_indicator.RMD file.

The python code is split into 3 parts: Linear Regression, Volatility, and ARIMA. Each part represents the objectives specified in the report. The sections before have the required python packages, as well sd utility functions that should be compiled before running the remainder of the file.

## Installation
### Requirements
Python 3.10 or later  
pip installer for Python  
The following Python libraries: pandas; numpy; matplotlib; seaborn; scipy; ta; sklearn; statsmodels; pmdarima

R  
The Following R packages:  
dplyr; rstanarm; ggplot2; sandwich; xts; msm; lubridate

Tableau  
Ensure Tableau Desktop is installed for visualizing exported data

## Execution
R Markdown File:
  * Run 'recall_indicator.Rmd' in RStudio to generate the 'recall_indicator.csv' (this will later be used as the recall indicator for the regression models and correlation analysis)

Jupyter Notebook:
  * Open 'Project_0_5.ipynb' in Jupyter Notebook
  * Execute the cells sequentially to perform the analysis

Tableau Visualization:
  * Use Tableau Desktop to import the csv files generated by the Python script
  * Refresh the Dashboard to visualize data for the regression models, correlation analysis, and ARIMA model
## Poster 
![finalPoster](https://github.com/markmcduffie/Recall-Project/assets/57467485/50244390-cd1d-4c86-a027-f5270c07a95a)
