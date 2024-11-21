# Big_4_Sports_Teams_and_City_Population_Analysis-2018-

## Overview

This project analyzes the performance of sports teams in four major leagues (NFL, NBA, MLB, and NHL) by calculating the correlation between win/loss ratios and the population of the metropolitan areas where the teams are based. It also explores whether teams from different sports within the same metropolitan area have similar performance metrics using paired t-tests. The analysis uses data from the 2018 sports season and population estimates from the 2016 U.S. Census.

## Dependencies and Installation

To run this project, you need to have Python installed along with the following dependencies:

- Python 3.12
- Pandas
- NumPy
- SciPy

You can install the required dependencies using the following command:  
-code: pip install pandas numpy scipy

---

## How to use

1. Clone this repository to your local machine:
- code: git clone https://github.com/username/repository_name.git

2. Navigate to the folder where you have cloned the repo:
- code: cd repository_name

3. Start Jupyter Notebook:
- code: jupyter notebook

4. Open the notebook of your choice and start exploring the content.

---

## Questions

The primary questions this analysis aims to answer are:
1. Is there a correlation between the win/loss ratio of sports teams and the population of their metropolitan area?
2. Do teams from different sports in the same metropolitan area show similar performance (in terms of win/loss ratios)?

---

## Datasets

The datasets used in this project are:
1. <a href="https://github.com/Lazycodes/Big_4_Sports_Teams_and_City_Population_Analysis-2018-/blob/main/nfl.csv">NFL.csv</a>
2. <a href="https://github.com/Lazycodes/Big_4_Sports_Teams_and_City_Population_Analysis-2018-/blob/main/nba.csv">NBA.csv</a>
3. <a href="https://github.com/Lazycodes/Big_4_Sports_Teams_and_City_Population_Analysis-2018-/blob/main/mlb.csv">MLB.csv</a>
4. <a href="https://github.com/Lazycodes/Big_4_Sports_Teams_and_City_Population_Analysis-2018-/blob/main/nhl.csv">NHL.csv</a>
5. <a href="https://github.com/Lazycodes/Big_4_Sports_Teams_and_City_Population_Analysis-2018-/blob/main/wikipedia_data.html">html file</a>

---

## Process

The process for this analysis includes the following steps:

- Data Cleaning:
  - Each dataset is cleaned to remove any inconsistencies and irrelevant columns.
  - Data is merged with population data based on the metropolitan area.

- Correlation Calculation:
  - The Pearson correlation coefficient is calculated between the win/loss ratio of teams and the population of the metropolitan area.

- Hypothesis Testing:
  - Paired t-tests are conducted to determine if there is a statistically significant difference in the performance of teams from different sports within the same metropolitan area.

- Results:
  - The correlation results are printed to show whether there is any meaningful relationship between the win/loss ratio and metropolitan population.
  - Paired t-test results show the p-values to assess the similarity of performance across sports teams.
 
---

## Acknowledgements:
This project is part of the Applied Data Science with Python Specialization from the University of Michigan. I would like to thank the university and the instructors for providing such valuable resources that helped me build and enhance my data science and Python skills throughout this project.






