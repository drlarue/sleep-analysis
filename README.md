# Analysis of Sleep Tracking Data

In this Jupyter notebook, I've analyzed sleep data from [Sleep as Android](http://sleep.urbandroid.org/), one of the most popular sleep tracking apps.

The app can back-up the data to Google Drive or Dropbox as a csv file, where each sleep record is saved onto 2 or 3 lines (see [here](http://sleep.urbandroid.org/documentation/developer-api/csv/) for the CSV file documentation).

Note: I manually inserted a row of headers before loading it into my notebook.

Browse through the notebook to see a summary of my analysis as well as all of the code and plots:

## Table of Contents
1. Predictors of Good Sleep: Executive Summary
2. Data Setup / Cleaning
3. Exploratory Analysis
4. Data Setup for Modelling
5. Deep Sleep Analysis
	1. LASSO
	2. LASSO as Variable Selection
		1. OLS
		2. Ridge
		3. Principal Components Regression
		4. Partial Least Squares
	3. Gradient Boosting Regression Trees
	4. Random Forest
		1. Treeinterpreter (Contribution Plots)
	5) Summary: Deep Sleep Predictive Models
6. "Above Average" Sleep Rating Classification
	1. Logistic Regression
	2. Gradient Boosting Classification Trees
	3. Random Forest
	 .  1. Treeinterpreter (Contribution Plots)
	5. Summary: Sleep Rating Predictive Models

Here is an example of the many plots that are in the notebook: 
![example_plot](https://user-images.githubusercontent.com/26487650/31189571-758bfaac-a8ed-11e7-86af-a23affe069ab.png)
