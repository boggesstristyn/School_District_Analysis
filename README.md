# School_District_Analysis

## Overview
The purpose of this project is to analyze data from an entire school district in order to visualize and showcase trends in school performance to assess current school standings and assist in the school board's future decision-making.

### Resources
Data files used for this analysis can be found: [Resources](https://github.com/boggesstristyn/School_District_Analysis/tree/main/Resources)

Software: Python 3.7, Anaconda 4.12, Jupyter Notebook.

## Results
During our analysis, we were informed the 9th graders at Thomas High School had shown evidence of academic dishonesty; in order to maintain state-testing standards, we replaced ninth grade reading and math scores from Thomas High School with NaNs and reevaluated the data.

- The revised district summary was affected in the Average Math Score, % Passing Math, % Passing Reading, and % Overall Passing categories.
  
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

Replacing the ninth-grade scores affect the following:

- Math and reading scores by grade
  
  **Original Math Scores:**
  
  <img width="290" alt="Original_math_scores" src="https://user-images.githubusercontent.com/103851131/169719953-ece26a10-f731-446d-9a08-eca3f3509637.png">
  
  **Revised Math Scores:**
  
  ![Revised_math_scores](https://user-images.githubusercontent.com/103851131/169719995-807d5f3d-4cde-46df-aa94-3c96b20d2240.png)
  
  **Original Reading Scores:**
  
  <img width="293" alt="Original_reading_score" src="https://user-images.githubusercontent.com/103851131/169720046-1b01c659-a2ea-4f87-a641-e292e5c76354.png">

  **Revised Reading Scores:**
  
  ![Revised_reading_score](https://user-images.githubusercontent.com/103851131/169720057-fabe19b1-91d2-4112-9f98-6df58c47256c.png)

- Scores by school spending
  
  **Original Spending Summary:**
  
  <img width="613" alt="Original_spending" src="https://user-images.githubusercontent.com/103851131/169720077-2c029a58-7675-4dfb-a6f3-827370b91010.png">

  **Revised Spending Summary:**
  
  <img width="613" alt="Revised_spending" src="https://user-images.githubusercontent.com/103851131/169720086-480ae247-51a4-4a39-9e7f-5a00b26cf38a.png">

- Scores by school size
  
  **Original School Size Summary:**
  
  <img width="613" alt="Original_size" src="https://user-images.githubusercontent.com/103851131/169720092-2db1e052-3ac9-4e93-bf61-6495f4982947.png">

  **Revised School Size Summary:**
  
  <img width="613" alt="Revised_size" src="https://user-images.githubusercontent.com/103851131/169720100-dccac878-cf81-4a4f-b1a1-cf973b19be9d.png">

- Scores by school type
  
  **Original School Type Summary:**
  
  <img width="613" alt="Original_type" src="https://user-images.githubusercontent.com/103851131/169720112-e1ea3ce6-208c-40e8-926a-b1dfba6153e6.png">

  **Revised School Type Summary:**
  
  <img width="613" alt="Revised_type" src="https://user-images.githubusercontent.com/103851131/169720122-632b9592-6bc3-460e-9781-db90c073ebee.png">

## Summary
In the updated school district analysis, after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs:

- The Average Math Score decreased by .1 from 79 to 78.9.
- The Average Reading Score remained unchanged at 81.9.
- The % Passing Math decreased by .2%, from 75% to 74.8%.
- The % Passing Reading decreased by .1%, from 85.8% to 85.7%.
- % Overall Passing decreased by .3%, from 65.2% to 64.9%.
