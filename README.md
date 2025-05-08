# College Major and Income Analysis: Does More Work Mean More Pay?

This repository contains the code, datasets, and visualizations for the project “Work-Life Balance vs. Earnings: Does More Work Mean More Pay?” The project analyzes how education level and college major group correlate with work hours and income, using data from Kaggle.

## Overview

This project explores the following research question:

Work-Life Balance vs. Earnings: Does More Work Mean More Pay?
We aim to investigate whether working more hours actually results in higher pay across different industries and education levels.

Why This Matters
Informed Decision-Making: Helps students and professionals evaluate trade-offs between hours worked and expected earnings.

Fair Compensation Design: Guides employers in assessing the efficiency and fairness of pay structures.

Policy Implications: Sheds light on productivity trends, diminishing returns from overwork, and long-term financial well-being.


### Interesting Insight

Higher Pay ≠ Longer Hours: Major groups like Health and Engineering report high incomes without working the longest hours. 

![2  Bar Chart: Median Earnings by Major](https://github.com/user-attachments/assets/1f773823-a215-4b45-89df-3361f9219f40)



## Repo Structure
 
Repository Content

Code

Final_Project.R

Reads, cleans, and merges adult_income.csv and college_majors.csv.

Maps education levels to major groups.

Calculates median earnings and hours worked.

Generates bar charts and boxplots for comparative insights.

Data
adult_income.csv
Demographic and employment data (education, income level, hours worked, etc.)

college_majors.csv
Median income and major group classification of college graduates.

Visuals
Saved plots include:
![2  Bar Chart: Median Earnings by Major](https://github.com/user-attachments/assets/480ff7b5-9aaa-41d0-9f7c-8bd07a1c072b)

Bar Chart: Median Earnings by Major Group.png: Bar chart showing median income by major group.


![1  Bar Chart: Education vs Median Hours Worked](https://github.com/user-attachments/assets/4647ceb3-b362-46d0-b340-5e7b102becaa)

Education vs Median Hours.png: Median hours worked per week by education level.


![Heatmap: Hours by Age Group and Education](https://github.com/user-attachments/assets/d8d55a03-2520-45c0-a011-d4a5e12ccce7)

Average Hours by Age Group and Education.png: Heatmap of hours by Age Group and Education. 

#Do you think we have to include all of the visualizations we have in this readme file? or this 3 are enough?

## How to Use

1. Clone the repository:

 ```bash
   git clone https://github.com/AmeeraSab/Sec1_FP_NurAmeeraSabrina_SiyonaBehera.git
   ```

2. Install R and RStudio. 
Required R packages to be installed:

  tidyverse

  ggplot2

3. Run Code Files
   
  Open the R scripts (data_cleaning.r, data_analysis_tables.r, data_visualizations.r) in RStudio.
  Run the scripts to load, clean, analyze, and visualize the data.

## Data Sources and Acknowledgements

Adult Income Dataset: Kaggle - Adult Census Income

College Majors Dataset: Kaggle - Economic Values of College Majors Data Analysis


## Authors

Siyona Behera: sbb6098@psu.edu

Nur Ameera Sabrina: njm6260@psu.edu
