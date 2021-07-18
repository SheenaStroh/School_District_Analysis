# School District Analysis

## Overview
After the initial analysis was completed the school board noted evidence of academic dishonesty and 
requested a new analysis based on this information. To complete this analysis the reading and math 
scores for Thomas High School 9th graders have been replaced with null values and the analysis was 
repeated. Following are the results and summary of that repeated analysis with the suspect values 
removed.

## Results
- The updated district summary shows that the overall district scores and percentages were barely 
affected by the updated data. This is expected since there were comparatively few affected grades with 
the total number of students. 
  ![Updated_district_analysis](https://user-images.githubusercontent.com/85318060/126084597-216028c5-4571-4d41-85c2-c6d652d578d6.PNG)

- The updated school summary shows that the new values for Thomas High School all went down slightly 
due to the updated data. This would be expected if the suspect grades that had been removed were 
initially inflated.
![Updated_school_summary](https://user-images.githubusercontent.com/85318060/126084974-b6fd1889-ccb9-460f-aad0-c62f2d64c436.PNG)

- Even after updating the results Thomas High School still maintains second place in overall 
performance, the new values did not make enough of an impact to affect their standing.

- In addition, the following summaries were also re-evaluated, and it was determined that none of them 
were affected by the change:
  - The math and reading scores by grade were recalculated, but the only difference was for the Thomas 
  High School 9th graders, whose scores are now listed as NaN. Since the affected scores were limited to 
  the one school and one grade, none of the other grades were affected.
  - The overall scores by school spending.
  ![Scores_by_per_student_spend](https://user-images.githubusercontent.com/85318060/126085361-9842f97e-277d-48f0-a223-1183e7d36588.PNG)
  - Scores by school size.
  ![scores_by_school_size](https://user-images.githubusercontent.com/85318060/126085412-1b67c18d-c582-488f-a1c3-7f82496e3701.PNG)
  - Scores by school type.
  ![Scores_by_school_type](https://user-images.githubusercontent.com/85318060/126085445-2f1720ff-2ddd-4886-81ad-70e4961c8658.PNG)

## Summary
In summary, the changes to the analysis were relatively minor for a majority of the values reported. The overall district summary scores went down very slightly. In the school summary for Thomas High School the averages and passing percentages all went down slightly. While the overall passing percentage for Thomas High School did go down, it did not go down significantly enough to affect their overall standing in the top 5 schools. The only other affect is in both the math and reading scores by grade, the Thomas High School 9th graders no longer have a value, their scores have been replaced with null values. The rest of the analysis was not affected significantly by the score alterations.
