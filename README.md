# school_district_analysis

## Purpose:
The purpose of this analysis was to investigate the claims of academic dishonesty among the 9th graders at Thomas High school.  We used data from schools_complete.csv and student_complete.csv to conduct or analysis.

## Results:
To complete our analysis, we removed the math and reading scores for the 9th graders at Thomas High School and then repeated our original analysis to compare the two.  Here are some of the key findings.

  * Distric Summary: The overall distric summary remained the same as compared to before the analysis.
  * School Summary: The school summary seemed to be affected by replacing the Thomas High School 9th grader scores with NaN's.  Thomas High school should low Math, Reading, and Overagll passing percentages, 67%, 70%, and 65% respectively.  However, this appears artificially low because the passing percentages are based off of total student count, which still included the 9th graders.  
  * Thomas High School Performance:  As stated above, removing the 9th graders scores appeared to severely impact the Math, Reading, and overall passing percentages at Thomas High School.  When we accounted for just the 10th, 11th, and 12th graders however, their passing perentages went back to what we found in our original analysis, 93%, 97%, and 90% respectively.
  * Math and Reading Scores by Grade: We found that the math and reading scores by grade were unchanged for Thomas High School and the rest of the schools.
  * Performance by school spending: Performance by school spending was not affected in our analysis.
  * Performance by school size: Performance by school size was not affected in our analysis.
  * Performancy by school type: Performance by school type was not affected in our analysis.


## Summary:
It does not appear there was academic dishonesty among the 9th graders at Thomas high school.  After removing them from the analysis we replicated the results from before, indicating that the 9th grade students math and reading scores were right around the average.  It makes sense that only removing a small subset of the entire district did not yeild major changes.  Perhaps chaning the focus of the analysis would allow us to detect smaller changes.  Analyzing just 9th graders across the school distric might show a difference between 9th graders at Thomas High School and all of the other schools.
