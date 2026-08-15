# Employee Data Cleaning and Exploratory Data Analysis

## Problem Statement
Employee turnover can be costly for a company due to expenses associated with recruitment, interviewing, and training new employees. Understanding the factors associated with employee turnover can help the company identify potential areas of concern, improve employee retention, and create a healthier and more supportive work environment.

## Project Overview
This project analyses a company's employee dataset to identify inconsistencies, duplicate records, missing values, and potential data quality issues. It also explores the factors associated with employee turnover to identify patterns that may influence an employee's decision to leave the company.

## Project Objectives
- Identify and clean data quality issues such as missing values, duplicates, inconsistencies, and invalid ranges.
- Perform exploratory data analysis to identify patterns in employee turnover.
- Identify key factors associated with employees leaving the company.
- Provide insights that could help the company improve employee retention.

## Dataset
The dataset is provided in CSV format and contains employee-level information relating to education, work location, compensation, and other employment characteristics. The dataset contains 4653 records and 9 variables, including the target variable. The target variable indicates whether an employee has left the company.

## Data Quality Issues
The only data quality issue identified was the presence of 1889 duplicated rows. 

## Data Cleaning Process
The data was cleaned by removing duplicate rows to ensure that the analysis of factors associated with employee turnover was accurate and reliable.

## Exploratory Data Analysis
Visualizations were used to analyze the distributions in the company and identify the factors associated with the company's employee turnover. 

The visualization below shows the distribution of employees who left versus those who stayed.
<img src="images/employee_turnover.png" width="600">

### Key Findings
- 39.4% employees left.
- The company has predominantly employed younger individuals.
- Majority of the employees hold a bachelor's degree.
- The company's gender distribution is relatively even
  
### The following factors are associated with employees leaving the company:
- Age: Younger employees have a higher turnover.
- Education: People holding a master's degree have a high turnover.
- Gender: Females have a high turnover.
- Joining Year: A large number of employees left in 2018, which is the most recent year of the dataset.
- Place of work: Employees employed at Pune have a high turnover.
- Benched employees: Employee who have never been unassigned with work have a low turnover. 

## Tools and Technologies
- Python
- pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure
- Data exploration
- Data cleaning
- Exploratory data analysis

## How to Run the Project
git clone <>

## Conclusion
The analysis successfully identified and addressed the duplicate records in the dataset. Exploratory data analysis revealed several patterns associated with employee turnover, including age, education, gender, joining year, work location, and whether employees had been temporarily unassigned from work. These insights can help the company better understand employee turnover and identify areas where employee retention strategies could be improved. 

## Future Improvements
- Future assess why employees in certain groups have a high turnover.
- Develop a machine learning model to predict employee turnover
