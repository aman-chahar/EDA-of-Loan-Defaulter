# Exploratory Data Analysis - Loan Defaulter
This project involves the analysis of two datasets, "application_data.csv" and "previous_application.csv," to gain insights into loan defaults and make data-driven decisions.

Kaggle URL to download the data:- https://www.kaggle.com/datasets/gauravduttakiit/loan-defaulter

1. **Data Import and Exploration**: The project starts by importing the required Python libraries and reading the two datasets, which contain information about loan applicants and their previous loan applications. Basic exploration of the datasets is performed to understand their structure.

2. **Feature Selection**: An initial feature selection process is carried out. Columns with a significant amount of missing data are removed. Additionally, columns starting with "FLAG_" are analyzed for their correlation with the target variable "TARGET," and some of them are dropped.

3. **Feature Engineering**: Feature engineering includes handling missing data and modifying or creating new columns. Missing data is imputed based on various strategies like using mode, median, or mean. New columns are also created to group or categorize data, such as income ranges, age groups, and credit amount ranges.

4. **Data Analysis**: The project then delves into data analysis. It involves a detailed examination of the data, including univariate analysis of both numeric and categorical variables. The analysis provides insights into the relationships between various attributes and the target variable, particularly focusing on identifying segments that are more likely to default on loans.

5. **Insights and Recommendations**: The project concludes with a section highlighting the main insights and recommendations. These insights are presented as a set of clear and actionable guidelines for a financial institution. The recommendations address which customer segments to target for loans, preferred income and credit amount ranges, and precautions to take when assessing loan applications. The recommendations aim to minimize loan defaults and make lending decisions more data-driven and informed.
