# Salary Prediction based on Job types 

## Problem Definition : Dataset consisting of training features, training target and test features are provided and aim is to perform exploratory data analysis and develop a machine learning model which will predict salaries based on job types.

## Introduction :
### The dataset contains information about 1 million people. It contains their salaries,job types, industry, education, major, years of experience and miles from metroplois, job and company Id.

## Exploratory Data Analysis

## 1) Importing Libraries
## 2) Loading the Data
## 3) Data Cleaning & Exploration
## 4) Data Visualization

## -------------------------------------------------------------------------------

## 1) Importing Libraries 
### Libraries used for exploratory data analysis are as follows:
### NumPy: NumPy is a python package.Full form is ' Numerical Python'. It is used for performing mathematical and statistical operations on arrays.
### Pandas: Pandas is a python library which is used for manipulating and analysing data using its strong data structures. Consists tools for loading data into in memory data objects from any file format, perform slicing, indexing and subsetting for various datasets and can handle missing values very well.
### Matplotlib: Matplotlib is a python library primarily used for data visualization such as creating figures and plots.
### Seaborn: Seaborn is a python library used for data visualization. It is built on top of Matplotlib and mainly used for creating statistical graphs. 

## 2) Loading the Data
### The three dataset files are loaded into python with the help of Pandas dataframe.

## 3) Data Cleaning & Exploration
### This process involves inspecting rows and columns of the datasets to identify any discrepancies, corrupt values, missing values, duplicated values, outliers etc. 
### In this project outliers are recognized using the Inter Quartile Range rule. It is a difference of the 75th percentile and 25th percentile. Consists of upper and lower bounds. Values greater than upper bound and less than lower bound are considered as outliers.

## 4) Data Visualization
### This process involves visualizing data and to understand the relation between each feature and the target variable i.e. salary.
