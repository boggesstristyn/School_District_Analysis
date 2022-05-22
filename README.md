# School_District_Analysis

## Overview
The purpose of this project is to analyze data from an entire school district in order to visualize and showcase trends in school performance to assist in the school board's 

Data given included 

preparing all standardized test data for analysis, reporting, and presentations to insghts about performance trends and patterns.
student funding and standardized test scores
aggregate the data and showcase trends in schoool performance. will assist school board in making decisions regarding the school budgets and priorities

### Resources
Data files used for this analysis can be found: [Resources](https://github.com/boggesstristyn/School_District_Analysis/tree/main/Resources)

Software: Python 3.7, Anaconda 4.12, Jupyter Notebook.

## Results
During our analysis, we were informed the 9th graders at Thomas High School had shown evidence of academic dishonesty; in order to maintain state-testing standards, we replaced ninth grade reading and math scores from Thomas High School with NaNs and reevaluated the data.

- The revised district summary was affected in the Average Mat Score, % Passing Math, % Passing Reading, and % Overall Passing categories.
  
  **Original District Summary:**
  ![Original_District_Summary](https://user-images.githubusercontent.com/103851131/169706887-76b909cd-9ca8-43d9-aa7d-8e1a168dea19.png)

  
  **Revised District Summary:**
  ![Revised_District_Summary](https://user-images.githubusercontent.com/103851131/169706895-a266bd4a-8a0b-4258-8feb-31a5ef04537d.png)

  
  - Average Math Score decreased from 79 to 78.9
  - % Passing Math decreased from 75 to 74.8
  - % Passing Reading decreased from 85.8 to 85.7
  - % Overall Passing decreased from 65.2 to 64.9

- After replacing the Thomas High School ninth graders' scores, the school summary was minimally affected, with Thomas High School still maintaining the same second place ranking.
  
  **Original School Summary:**
  ![Original_School_Summary](https://user-images.githubusercontent.com/103851131/169707102-94d3e7a8-6ac8-4ef4-b988-7cc20782de4f.png)

  
  **Revised School Summary:**
  ![Revised_School Summary](https://user-images.githubusercontent.com/103851131/169707100-fdb4c604-ecb5-4997-b3bb-6aeb980b5da4.png)

- Replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
  - Scores by school spending
  - Scores by school size
  - Scores by school type

## Summary
In the updated school district analysis, after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs:

- The Average Math Score decreased by .1 from 79 to 78.9.
- The Average Reading Score remained unchanged at 81.9.
- The % Passing Math decreased by .2%, from 75% to 74.8%.
- The % Passing Reading decreased by .1%, from 85.8% to 85.7%.
- % Overall Passing decreased by .3%, from 65.2% to 64.9%.
