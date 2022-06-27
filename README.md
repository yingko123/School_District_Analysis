# School District Analysis<br>

## Overview of the school district analysis:<br>
Using tools in the Pandas library, we analyized school and student academic data of the PyCity school district.  The analysis focus on whether there are correlation between academic performance and school type, funding ,and size.  We then look at if academic data of Thomas High School's ninth graders contain any signs of academic dishonesty by replacing the scores in question with NaN. 

## Results:
<br>
* District Summary:<br>
Replacing scores of Thomas High School's 9th graders with NaN resulted in slightly lower academic passing rate for the district.  For math it lowered from 75% to 74.8%. For reading, it lowered from 85.8% to 85.7%.  This also resulted in lower overall passing rate from 65.2% to 64.9%.<br>
<br>
<img src="Resources/District_Summary_Compare.PNG"><br>
<br>

* School Summary:<br>
Replacing Thomas High School 9th grader scores has no affect on the results of other high schools (see school summary from every school in the Per School Summary table in below Thomas High School segment). <br>
<br>
* Thomas High School Performance:<br>
Replacing 9th grader scores lower the overall Thomas High School academic results slightly.  
<br>
<img src =  "Resources/Schools_w_Thomas_adj.png">

* Other affect:<br>
    - Math and reading scores by grade - replacing Thomas High School 9th grader's scores only affected the scores for this particular group.  All other schools and their per grade scores has no impact.

    <img src = "Resources/Scores by Grade.PNG">

    - Scores by school spending - 
     
## Summary

