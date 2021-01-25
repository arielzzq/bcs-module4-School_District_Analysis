# An Analysis on Student Performance in a School District with 15 High Schools

## Overview of the analysis
### Purpose
The purposes of this analysis are listed below:
- To analyse the relationship between student performance (math and reading scores) and grade, school spending, school size and school type respectively.
- To explore how ommiting the scores for Thomas High School ninth graders can affect the result of school district analysis.

## Results
The effects of removing the scores for Thomas High School (THS) ninth graders on the the school district analysis are shown below:
### Effects on District Summary
- The average math score and the passing rate for math were decreased. 
- The average reading score remained the same, but the passing percentage for reading dropped from 85.8% ot 85.7%. 
- The overall passing rate of the district decreased from 65.2% to 64.9%.
- Whether the changes were statistically significant was unknown.

![District_summary_1](Resources/images/District_summary_1.png)
![District_summary_2](Resources/images/District_summary_2.png)

### Effect on School Summary
- Since we only changed the data for THS, the change didn't affect the summary for other schools.
- All of the result related to THS scores were altered as shown in the red squares in 2 figures below
    - The average math score, and the passing rate for math dropped.
    - The average reading score increased while the passing rate for reading decreased.
    - The overall passing percentage dicreased from 90.948012% to 90.630324%
    
    ![School_summary_1](Resources/images/School_summary_1.png)
    ![School_summary_2](Resources/images/School_summary_2.png)
    
### Effect on performance ranking
- There was no effect on Thomas High School’s performance relative to the other schools.
- THS was still the second place on the overall passing percentage ranking.

![top_five_1](Resources/images/top_five_1.png)
![top_five_2](Resources/images/top_five_2.png)

### Effect on Group Analysis
- Math and reading scores by grade
    - There was no effect on 10th, 11th and 12th grades.
    - There was no effect on 9th grade for schools other than THS.
    - The math and reading scores for THS 9th grade became NaN after the change.
    
    - Math Score Figures
    
        ![math_by_grade_1](Resources/images/math_by_grade_1.png) 
        ![math_by_grade_2](Resources/images/math_by_grade_2.png)
        
    - Reading Score Figures
    
        ![reading_by_grade_1](Resources/images/reading_by_grade_1.png)
        ![reading_by_grade_2](Resources/images/reading_by_grade_2.png)
        
- Scores by school spending
    - THS was in "$630-644" spending bin, there was no effect on other bins.
    - After formatting the data frame, there was no effect on the "$630-644" bin as well.
    
    ![spending_1](Resources/images/spending_1.png)
    ![spending_2](Resources/images/spending_2.png)
    
- Scores by school size
    - THS was in "Medium (1000-2000)" size bin, there was no effect on other bins.
    - After formatting the data frame, there was no effect on the "Medium (1000-2000)" bin as well.
    
    ![size_1](Resources/images/size_1.png)
    ![size_2](Resources/images/size_2.png)
    
- Scores by school type
    - After formatting the data frame, there was no effect.
    
    ![type_1](Resources/images/type_1.png)
    ![type_2](Resources/images/type_2.png)
    
   
## Summary
After reading and math scores have been replaced for Thomas High School ninth graders. The average math score, passing rate for math, passing rate for reading and the overall passing rate for the school district decreased. All of the results associate with scores for THS decreased except for the average reading score, it increasd from 83.84 to 84.89. The change didn't affect THS's performance relative to other school, and had no detectable effect on group analysis after rounding the data.
