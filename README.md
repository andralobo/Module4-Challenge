# School District Analysis 
## Overview of the School District Analysis
### Purpose
The School Board has requested an analysis on the reading and math grades for the school district.  It seems there has been academic dishonesty at Thomas High School for grade 9 math and reading tests.  We have been asked to remove these grades from our analysis so they can uphold state-testing standards and compare our results from the analysis before removing them.

We have been asked to change the math and reading marks for grade nines from Thomas High School to NaNs while keeping the remainder of the data in the report.



## School District Analysis Results

How is the district summary affected?

The district summery overall only showed a very small change.

Original Analysis
<img src="https://github.com/andralobo/Module4-Challenge/blob/main/Resources/District_Summary_before.png?raw=true">

After removing Thomas High School
<img src="https://github.com/andralobo/Module4-Challenge/blob/main/Resources/District_Summary_after.png?raw=true">




-  In the School Summary this update only affected Thomas High School's summary.  There was no impact on the other school 

Original Analysis -  You can see Thomas High School is highlighted in Yellow
<img src="https://github.com/andralobo/Module4-Challenge/blob/main/Resources/School_Summary_before.png?raw=true">

After removing Thomas High School
<img src="https://github.com/andralobo/Module4-Challenge/blob/main/Resources/School_Summary_after.png?raw=true">


-  The % change for Thomas High School overall was very small for reading, math and overall percentages

-  Replacing the ninth-grade scores affect the following:
    - The grade 9 math and reading grades are now 0.  Thomas High School went from the top 5 reading and 3rd in math to 0.
    - The numbers for school spending for Thomas High School are still incorrect.  The #'s fo students should have been updated in per_school_summary_df.  The number of Students is still 1635 when it should be 1174.
    - Thomas High School was a in the medium (1000-2000 student) sized groud. The scores and percentages went up a small amount when the analysis was rerun for the Scores by School size.
	
       Below are the scores before: 
	<img src="https://github.com/andralobo/Module4-Challenge/blob/main/Resources/Score_Summary_before.png?raw=true">
	
	Below are the Scores after removing Thomas High School:	
	<img src="https://github.com/andralobo/Module4-Challenge/blob/main/Resources/Score_Summary_after.png?raw=true">
	
    - Thomas High School is a Charter School and after reveiwing the before and after reports for scores by school types, the numbers are exactly the same



## School District Analysis Summary

The total number of students changed from 39,170 to 38,709 and the number of students at Thomas High School changed from 1,635 to 1,174 after removing the 461 grade 9 students from Thomas High School.

In the District Summary the math scores showed more of and decrease over the reading scores.  The average math score went from 79.0 to 78.9 which decreased the passing math percentage from 75.0 % to 74.8%. 

Thomas High School went from the top 5 in reading and 3rd in math to 0.

Thomas High School was a in the medium (1000-2000 student) sized group. The scores and percentages went up a small amount when the analysis was rerun for the Scores by School size.  The overall Passing Percentage went from 90.61% to 90.56.
