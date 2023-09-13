# Data-Science-Job-Education-and-Salary-Analysis
This repository analyzes the evolving landscape of Data Science roles, focusing on in-demand skills and highest-paying positions using data from Kaggle and ai-jobs.net. A valuable resource for educational institutions, companies, and aspiring Data Scientists.

# Overview
This repository contains an Exploratory Data Analysis (EDA) focused on the Data Science job market, including job titles, salary trends, and required skills. The analysis uses datasets from Kaggle's annual Machine Learning & Data Science survey and ai-jobs.net's salary surveys to gain a comprehensive understanding of market trends from 2018 to 2022.

#Data Sources
Kaggle's Machine Learning & Data Science Survey (2018, 2019)
ai-jobs.net Salary Survey (2020-2022)

# Dataset Attributes
ai-jobs.net Dataset: work_year, experience_level, employment_type, job_title, salary, salary_currency, salary_in_usd, employee_residence, remote_ratio, company_location, company_size.
Kaggle Dataset: Various attributes related to Data Science skills and preferences.

# Preprocessing Steps
Null values: Checked and found no null values.
Data type conversion: String-to-category for experience_level, employment_type, remote_ratio, and company_size.
Dropped Columns: Removed "salary" and "salary_currency" to streamline analysis with "salary_in_usd".

# Objectives
Understand the correlation between various attributes like experience level, employment type, and salary in USD.
Identify key skills that are prevalent and sought-after in the Data Science market.
