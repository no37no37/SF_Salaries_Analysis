## SF Salaries Analysis Project

### Introduction
The "SF Salaries Analysis" project focuses on exploring and analyzing salary data of San Francisco city employees. The dataset, obtained from [Kaggle](https://www.kaggle.com/datasets/kaggle/sf-salaries), provides information about employee names, job titles, base pay, overtime pay, benefits, and more.

### Data Loading and Overview
The project begins by loading the dataset using the Pandas library. The top and bottom 10 rows of the dataset are displayed to get a quick overview.

### Dataset Shape
The shape of the dataset is examined to understand the number of rows and columns. In this case, there are 148,654 entries and 13 columns.

### Dataset Information
A detailed information summary of the dataset is provided, including the count of non-null values, data types of each column, and memory usage. This information is crucial for understanding the structure of the dataset.

### Handling Missing Values
The project checks for null values in the dataset, and the number of missing values in each column is displayed. Additionally, columns with less relevance, such as 'Id', 'Notes', 'Agency', and 'Status', are dropped.

### Descriptive Statistics
An overview of descriptive statistics for numerical columns is presented. This includes information such as mean, standard deviation, minimum, and maximum values.

### Employee Information
The project explores employee-related information, such as finding the occurrence of employee names and identifying unique job titles. The top 5 most common job titles are also displayed.

### Specific Job Title Analysis
Specific analyses are conducted, including finding the number of job titles containing "Captain" and displaying the names of employees in the fire department.

### BasePay Analysis
Analysis on BasePay involves finding the minimum, maximum, and average BasePay, handling 'Not Provided' values, and identifying the person with the highest BasePay.

### Grouped Analysis
The project groups the data to find average BasePay per year, average BasePay per job title, and the average BasePay for employees with the job title 'ACCOUNTANT'.

### Conclusion
This documentation provides a comprehensive overview of the "SF Salaries Analysis" project, highlighting key data exploration and analysis steps. The insights gained from this analysis can be valuable for understanding salary distributions and trends among San Francisco city employees.
