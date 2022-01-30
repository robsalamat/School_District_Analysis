# School_District_Analysis

## I. Overview of Project

### Background
Maria, the chief data scientist of the city school district, was tasked with analyzing data on student funding and standardized test scores in order to showcase trends and pattern.

### Objective
After the analysis, it was discovered that grades for Thomas High School ninth graders appear to have been altered. Now, the goal is to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact, then repeat the school district analysis and report how the changes affected the overall analysis.

## II. [Analysis and Results](PyCitySchools_Challenge.ipynb)

The Math and Reading scores were replaced with NaNs using:
![](Resources/NaN.PNG)

### A. Effect on District Summary

![](Resources/District_Summary.png)

The new edited values are slightly lower than the original values. The District % Overall Passing became lower by 0.3.

### B. Effect on School Summary

![](Resources/School_Summary.png)

The school performance also became slightly lower than the orginal values. The school's % Overall Passing also became lower by 0.3.

### C. Thomas High School’s performance relative to the other schools

![](Resources/THS_Performance.png)

For Thomas High School's performance relative to other schools, it retained the Top 2 spot even with a lower % Overall Passing.

### D. Replacing the ninth-grade scores effect on the following:

  - **Math and reading scores by grade**
  
  ![](Resources/Scores_by_Grade.png)
  
  The 9th graders' math and reading scores are just replaced by NaN.
  
  - **Scores by school spending**
   
  ![](Resources/Scores_by_Spending.png)
  
  There is no change for the scores by school spending.
  
  - **Scores by school size**
  
  ![](Resources/Scores_by_Size.png)
  
  There is no change for the scores by school size.
  
  - **Scores by school type**

  ![](Resources/Scores_by_Type.png)

  There is no change for the scores by school type.

## III. Summary

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

