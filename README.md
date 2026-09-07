# ABC-Company-Data-Analysis


## 1.Project Overview

This project analyzes the ABC company employee  dataset to understand the distribution of employees across teams, positions, age groups, and salary expenditure. The project also examines the relationship between employee age and salary using correlation analysis.
The analysis was performed using Python, Pandas, Matplotlib, and Seaborn in a Jupyter Notebook. Various data analysis techniques and graphical representations were used to identify important trends, patterns, and relationships in the dataset.

## 2.Objectives

The main objectives of this project are:

- To understand the distribution of employees across different teams.
- To analyze employee distribution across different positions.
- To identify the most common age groups.
- To compare salary expenditure across teams.
- To compare salary expenditure across different positions.
- To determine the relationship between age and salary.
- To present the findings using suitable visualizations.

 ## 3.Tools and Technologies Used

- Python
- Jupyter Notebook
- Pandas – Data loading, cleaning, preprocessing, and analysis
- NumPy – Numerical operations
- Matplotlib – Data visualization
- Seaborn – Statistical visualization

 ## 4.Data Preprocessing
  The following preprocessing activities are performed:
  
 - Load the dataset into a Pandas DataFrame.
 - Inspect the first and last records.
 - Check the number of rows and columns.
 - Review column names and data types.
 - Check for missing values.
 - Verify that Age and Salary are numeric.
 - Remove or handle invalid/missing records where necessary.
 - Create age groups for age-based analysis.
 - Prepare grouped and aggregated data for analysis

## 5.Analysis Tasks

**Task 1: Determine the distribution of employees across each team and calculate the percentage split relative to the total number of employees.**

   -The number and percentage of employees in each team were analyzed to understand workforce distribution.
   
    Graphical Representation: A bar chart was used to visualize the number of employees in each team.

Key Insight:

- Employees are distributed across 30 different teams.
- The New Orleans Pelicans have the highest number of employees, with 19 employees (4.15%).
- The Memphis Grizzlies have 18 employees (3.93%).
- Most teams have around 15 employees (approximately 3.28%).
- The Orlando Magic and Minnesota Timberwolves have the lowest number, with 14 employees each (3.06%).
- Overall, the workforce is relatively evenly distributed across teams.


**Task 2: Segregate employees based on their positions within the company.**

   -The number of employees in each position was analyzed.
 
    Graphical Representation: A bar chart was used to compare employee counts across positions.

Key Insight:

- SG has the highest number of employees, with 102 employees.
- C has the lowest number, with 79 employees.
- Overall, employee distribution across positions is relatively balanced.



**Task 3: Identify the predominant age group among employees.**

   -Employees were grouped into different age ranges to understand the age composition of the workforce.
 
       Graphical Representation: A bar chart was used to show the number of employees in each age group.


 Key Insight:

- The 26–32 age group is the largest, with 202 employees.
- The 18–25 age group has 200 employees.
- The 33–40 age group has the lowest representation, with 56 employees.
- Overall, the workforce is predominantly made up of employees aged 18–32.

 **Task 4: Salary Expenditure by Team**

   -Total salary expenditure was calculated for each team.

        Graphical Representation: A bar chart was used to compare total salary expenditure across teams.

Key Insight:

- The Cleveland Cavaliers have the highest salary expenditure, with 106,988,689.
- The Los Angeles Clippers have salary expenditure of 94,854,640.
- The Oklahoma City Thunder have salary expenditure of 93,765,298.
- The Philadelphia 76ers have the lowest salary expenditure, with 30,992,894.
- Salary expenditure varies considerably across teams.



**Task 5: Salary Expenditure by Position**

  -Total salary expenditure was calculated for each employee position.

     Graphical Representation: A bar chart was used to compare salary expenditure across positions.

Key Insight:

- C has the highest salary expenditure, with 466,377,332.
- PG has the second-highest expenditure, with 446,848,971.
- PF has 442,560,850.
- SF has 408,020,976.
- SG has the lowest salary expenditure, with 396,976,258.
- Overall, C accounts for the highest total salary expenditure among the positions.

 **Task 6: Relationship Between Age and Salary**

  -The correlation between employee age and salary was calculated.

     Graphical Representation: A scatter plot and heatmap were used to analyze the relationship and correlation between age and salary.

Correlation: "0.214"

Key Insight:

- The correlation coefficient of 0.214 indicates a weak positive correlation between age and salary.
- This means salary tends to increase slightly as age increases.
- However, the relationship is weak, suggesting that age alone is not a strong predictor of salary.

## 6.Overall Data Story

* The dataset contains employees distributed across 30 teams, with a relatively balanced workforce distribution. The New Orleans Pelicans have the highest  number of employees with 19, while the Orlando Magic and Minnesota Timberwolves have the lowest with 14 each.
* Across positions, SG has the highest number of employees with 102, while C has the lowest with 79. This indicates that the workforce is fairly balanced across positions.
* The workforce is mainly concentrated in the 18–32 age range, with the 26–32 age group being the largest group with 202 employees.
* Salary expenditure varies considerably across teams. The Cleveland Cavaliers have the highest total salary expenditure at 106,988,689, while the Philadelphia 76ers have the lowest at 30,992,894.
* When salary expenditure is analyzed by position, C has the highest total expenditure at 466,377,332, followed by PG and PF. SG has the lowest total salary expenditure among the positions.
* The correlation between age and salary is 0.214, indicating a weak positive relationship. Therefore, factors other than age are likely to have a greater influence on salary.


### 7.Key Findings

| Analysis | Key Finding |
|---|---|
| Team Distribution | New Orleans Pelicans have the highest employee count |
| Position Distribution | SG has the highest employee count |
| Age Distribution | 26–32 is the largest age group |
| Highest Team Salary | Cleveland Cavaliers |
| Lowest Team Salary | Philadelphia 76ers |
| Highest Position Salary | C |
| Lowest Position Salary | SG |
| Age-Salary Correlation | 0.214 – Weak Positive Correlation |

## 8.Conclusion
* Overall, the analysis shows that employees are relatively evenly distributed across teams and positions. Most employees belong to the 18–32 age range, with the 26–32 group having the highest representation.
* Salary expenditure shows considerable variation across both teams and positions. The Cleveland Cavaliers have the highest team-level salary expenditure, while the C position has the highest total salary expenditure.
* The weak positive correlation of 0.214 between age and salary suggests that salary tends to increase slightly with age, but age alone does not strongly determine salary. Other factors such as position, experience, performance, and team-level factors may have a greater influence on salary.


## 9.Project Files

- "ABC.ipynb" – Jupyter Notebook containing the complete analysis, Python code, visualizations, and findings.
- "README.md" – Project overview, preprocessing steps, analysis tasks, visualizations, insights, and conclusion.
- "ABC Company" – ABC company employee dataset

## 10.How to Run the Project

1. Download or clone the project repository.
2. Open the Jupyter Notebook file.
3. Make sure the required Python libraries are installed.
4. Place the dataset in the appropriate project directory.
5. Run the notebook cells sequentially.
6. Review the generated tables, graphs, and analysis results.

## 11.Required Libraries

- import pandas as pd
- import numpy as np
- import matplotlib.pyplot as plt
- import seaborn as sns

## 12.Final Outcome

This project demonstrates the use of data preprocessing, exploratory data analysis, aggregation, correlation analysis, and data visualization to extract meaningful insights from an employee dataset.
