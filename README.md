Jobberman Job Dataset Analysis

Overview
This project explores and analyzes a Jobberman job dataset using Python.
The goal is to understand job roles, salary distribution, and other useful insights from the dataset.

The analysis was performed using Pandas and Python in a Jupyter Notebook.

Objectives
The analysis focuses on:
  Understanding the structure of the dataset
  Cleaning and preparing the data
  Exploring salary distribution across job roles
  Identifying the highest paying job descriptions
  Performing basic exploratory data analysis (EDA)

Tools Used
  Python
  Pandas
  Numpy

Dataset
The dataset contains information about job listings including:
  Job description
  Salary
  Job roles
  Other related attributes

Key Analysis Performed
Some of the analysis carried out include:
  Inspecting dataset structure and column types
  Handling missing values
  Grouping job descriptions by salary
  Identifying highest paying job roles

Example analysis:
df.groupby('Job_Description')['Salary'].sum().sort_values(ascending=False)

Key Insight
From the analysis, some job roles show significantly higher salary totals compared to others, giving insight into the most lucrative positions in the dataset.
