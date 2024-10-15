# Employee Data Preprocessing

## Overview

This project focuses on designing and implementing a robust data preprocessing system for an employee dataset. The goal is to address common challenges such as missing values, outliers, inconsistent formatting, and noise, ultimately enhancing the quality and reliability of the data for machine learning applications.

## Dataset

The dataset used in this project is named `Employee.csv`, which contains the following columns:

- **Company**: The name of the company where the employee works.
- **Age**: The age of the employee.
- **Salary**: The salary of the employee.
- **Place**: The city where the employee is located.
- **Country**: The country of residence (all entries are from India).
- **Gender**: Gender of the employee (noted as 0 or 1).

### Sample Data

| Company | Age | Salary | Place     | Country | Gender |
|---------|-----|--------|-----------|---------|--------|
| TCS     | 20  |        | Chennai   | India   | 0      |
| Infosys | 30  |        | Mumbai    | India   | 0      |
| TCS     | 35  | 2300   | Calcutta  | India   | 0      |
| ...     | ... | ...    | ...       | ...     | ...    |

## Objectives

1. **Data Exploration**: Analyze unique values and perform statistical analysis.
2. **Data Cleaning**: Address missing values, remove duplicates, and identify outliers.
3. **Data Analysis**: Filter data based on specific criteria and visualize distributions.
4. **Data Encoding**: Convert categorical variables into numerical representations.
5. **Feature Scaling**: Normalize feature values to improve model performance.

## Visualizations

- Scatter plots to visualize the relationship between Age and Salary.
- Bar charts to showcase the distribution of employees from different places.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/D-K02/Data-Preprocessing-Employee.git
