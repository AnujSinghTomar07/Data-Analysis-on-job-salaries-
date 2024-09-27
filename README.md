# Exploratory Data Analysis on Job Salaries in Data Science 

## Overview

This repository contains an exploratory data analysis (EDA) of job salaries in the Data Science field. The analysis is based on a dataset that includes information about salaries, job titles, and other employment-related features.

## Dataset Overview

The dataset contains the following features:

- **work_year**: The year the salary was paid.
- **experience_level**: The experience level of the employee. Possible values:
  - EN: Entry-level / Junior
  - MI: Mid-level / Intermediate
  - SE: Senior-level / Expert
  - EX: Executive-level / Director
- **employment_type**: The type of employment. Possible values:
  - PT: Part-time
  - FT: Full-time
  - CT: Contract
  - FL: Freelance
- **job_title**: The role worked in during the year.
- **salary**: The total gross salary amount paid.
- **salary_currency**: The currency of the salary paid (ISO 4217 currency code).
- **salary_in_usd**: The salary amount converted to USD.
- **employee_residence**: The employee's primary country of residence (ISO 3166 Alpha-2 country codes).
- **remote_ratio**: The overall amount of work done remotely. Possible values:
  - 0: No remote work
  - 50: Partially remote
  - 100: Fully remote
- **company_location**: The country of the employer's main office (ISO 3166 Alpha-2 country codes).
- **company_size**: The size of the company. Possible values:
  - S: Small (less than 50 employees)
  - M: Medium (50 to 250 employees)
  - L: Large (more than 250 employees)

## Data Preparation

- **Removing Unnecessary Columns**: Dropped the 'Unnamed: 0' column and 'salary_currency' column.
- **Mapping Values**: Converted feature values to more descriptive labels for better understanding.
- **Handling Missing Values and Duplicates**: Checked for missing values and duplicates; cleaned the dataset accordingly.
- **Outlier Detection and Removal**: Identified and removed outliers in salary data.

## Exploratory Data Analysis

- **Distribution of Salaries by Job Title**: Visualized the highest salaries by job title.
- **Average Salary Analysis**: Analyzed average salaries by experience level, company size, employment type, and remote ratio. Compared salaries for full-time vs. contract-based employees.
- **Top Paying Countries**: Analyzed salaries by country and identified the highest paying countries.
- **Highest Earning Jobs**: Determined the highest earning job titles in top paying countries and by experience level.
- **Salary Trends**: Investigated salary trends over the years for Data Science roles and for medium-sized companies.

## Key Findings

- **Highest Salary by Job Title**: The job title with the highest salary is Lead Data Engineer with a salary of $276,000.
- **Average Salary by Experience Level**: Executive-level roles have the highest average salary.
- **Company Size Impact**: Medium-sized companies offer higher average salaries compared to small and large companies.
- **Employment Type**: Contract-based employees earn more on average than full-time employees.
- **Remote Work**: Employees working fully remote earn more on average compared to those with no remote work.
- **Top Paying Countries**: Russia (RU) offers the highest average salary, followed by the US.

## Code and Analysis

The analysis is performed using Python with libraries such as Pandas, NumPy, Matplotlib, and Seaborn. The code includes data loading, cleaning, and visualization steps.
