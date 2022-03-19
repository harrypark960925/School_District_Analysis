# School District Analysis

## Overview of the project 
The school board has notified that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned for help. The school wants to repalce the math and reading score for Thomas High School with NaNs while keeping the rest of the data intact. 

## Summary of the results 
### How is District Summary affected? 
The images below are the average math and reading scores of the school with percentage of passing the tests before and after removing the ninth graders' grades. We can see that there are bit of changes on numerical values after we removed ninth graders' grades. 
<img width="1178" alt="Screen Shot 2022-03-19 at 5 32 58 PM" src="https://user-images.githubusercontent.com/83077836/159139095-60f814e6-77f5-46a1-9027-c8397dd6b8ef.png">
<img width="1180" alt="Screen Shot 2022-03-19 at 5 31 21 PM" src="https://user-images.githubusercontent.com/83077836/159139055-3a1a1ae6-21e7-4d2a-8c11-7f5358a5c65d.png">
- Avergae Math Score: decreased to 78.9 from 79.0 
- Average Reading Score: No change 
- % Passing Math: decrased to 74.8% from 75.0% 
- % Passing Reading: decreased to 85.7% from 86.0%
- % Overall Passing: decreased to 64.9% from 65.0% 

### How is School Summary affected? 
The images below are the school summary of each school. If you look at the Thomas High School row, which is at the very bottom line, the number of total students is same but the numerical value of average math and reading scores have been changed. Automatically, % passing math, reading and overall have been changed too. 
<img width="994" alt="Screen Shot 2022-03-19 at 5 57 14 PM" src="https://user-images.githubusercontent.com/83077836/159140444-b13ab10d-322d-4d2d-97e6-eb4e0c4eaabd.png">
<img width="994" alt="Screen Shot 2022-03-19 at 5 56 52 PM" src="https://user-images.githubusercontent.com/83077836/159140458-87ee23da-37a0-4644-a9b8-268b3a63c186.png">
- Avergae Math Score: decreased to 83.35 from 83.41 
- Average Reading Score: increased to 83.89 from 83.85 
- % Passing Math: decrased to 93.19% from 93.27% 
- % Passing Reading: decreased to 97.02% from 97.31%
- % Overall Passing: decreased to 90.63% from 90.95% 

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- After replacing the ninth graders' math and reading scores, Thomas High School is no longer placed on the top five schools for the grade
<img width="1194" alt="Screen Shot 2022-03-19 at 6 32 27 PM" src="https://user-images.githubusercontent.com/83077836/159140751-cb0fd628-4290-42b5-9d30-c1886753dd22.png">
This is when Thomas High School's ninth graders' math and reading scores are included. 

<img width="1092" alt="Screen Shot 2022-03-19 at 6 33 55 PM" src="https://user-images.githubusercontent.com/83077836/159140752-f3722ff2-57cc-4e1e-9dd7-90d3cf323b50.png">
This is when Thomas High School's ninth graders' math and reading scores are removed. 


### How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade: Thomas High School 9th graders' grades were removed but everything else is same. 
<img width="893" alt="Screen Shot 2022-03-19 at 6 39 35 PM" src="https://user-images.githubusercontent.com/83077836/159141846-e56b3372-436c-435c-ae74-db31fa56ff08.png">
Math scores before removing Thomas High School's 9th graders 
<img width="883" alt="Screen Shot 2022-03-19 at 6 39 44 PM" src="https://user-images.githubusercontent.com/83077836/159141849-77631559-c361-45fa-b1ce-29a00ee68935.png">
Math scores after removing Thomas High School's 9th graders 
<img width="900" alt="Screen Shot 2022-03-19 at 6 39 59 PM" src="https://user-images.githubusercontent.com/83077836/159141858-0c7f9247-76e0-41a2-b660-dfbe0fae6461.png">
Reading scores before removing Thomas High School's 9th graders 
<img width="895" alt="Screen Shot 2022-03-19 at 6 40 09 PM" src="https://user-images.githubusercontent.com/83077836/159141860-ad4c7469-da21-4890-91bc-75eaca5776a6.png">
Reading scores after removing Thomas High School's 9th graders 

- Scores by school spending: Thomas High School Spending Range is $631 ~ 645 per student and the following scores have been changed in this range. 
  - Average Math Score: 78.52 -> 78.50 (decreased) 
  - Average Reading Score: 81.62 -> 81.64 (increased) 
  - % Passing Math: 73.48 % -> 73.46 % (decreased) 
  - % Passing Reading: 84.39 % -> 84.32 % (decreased) 
  - % Overall Passing: 62.85 %  -> 62.78 % (decreased) 
  <img width="1086" alt="Screen Shot 2022-03-19 at 7 39 15 PM" src="https://user-images.githubusercontent.com/83077836/159142083-623745bf-615c-4082-a2ed-f1f8941e250d.png">
  Spending summary before removing Thomas High School's 9th graders 
<img width="1064" alt="Screen Shot 2022-03-19 at 7 40 06 PM" src="https://user-images.githubusercontent.com/83077836/159142087-dfe91310-2a27-463f-b637-b89712a79a7a.png">
  Spending summary after removing Thomas High School's 9th graders 

- Scores by school size: Thomas High School is a medium sized school and the following scores have been changes in the medium size. 
  - Average Math Score: 83.37 -> 83.36 (decreased) 
  - Average Reading Score: 83.86 -> 83.87 (increased) 
  - % Passing Math: 93.60 % -> 93.58 % (decreased) 
  - % Passing Reading: 96.79 % -> 96.73 % (decreased) 
  - % Overall Passing: 90.62 %  -> 90.56 % (decreased)

- Scores by school type: Thomas High School is a charter type and the following scores have been changes in charter type. 
  - Average Math Score: 83.474 -> 83.465 (decreased) 
  - Average Reading Score: 83.896 -> 81.902 (increased) 
  - % Passing Math: 93.62 % -> 93.61 % (decreased) 
  - % Passing Reading: 96.59 % -> 96.55 % (decreased) 
  - % Overall Passing: 90.43 %  -> 90.39 % (decreased)

### Summary 
Although the changes are very small so that the format should go up to three decimal points, because of the academic dishonesty of 9th graders in Thomas High School, overall passing percentage has been decreased to Thomas High School. The biggest change that we can see from removing 9th graders' grades, Thomas High School is no longer placed in top five schools for grades. However, the average reading score has increased slightly but everything else has been decreased for all categories: school spending, school size, school type, math and reading scores by grade. 
