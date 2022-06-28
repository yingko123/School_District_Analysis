# School District Analysis<br>

## Overview of the school district analysis:<br>
Using tools in the Pandas library, we analyized school and student academic data of the PyCity school district.  The analysis focus on whether there are correlation between academic performance and school type, funding ,and size.  We then look at if academic data of Thomas High School's ninth graders contain any signs of academic dishonesty by replacing the scores in question with NaNs. 

## Results:

* District Summary:<br>
Replacing scores of Thomas High School's 9th graders with NaNs resulted in slightly lower academic passing rate for the district.  For math it lowered from 75% to 74.8%. For reading, it lowered from 85.8% to 85.7%.  This also resulted in lower overall passing rate from 65.2% to 64.9%.<br>
<br/>
<img src="Resources/District_Summary_Compare.PNG"><br>
<br>

* School Summary:<br>
Replacing Thomas High School 9th grader scores has no affect on the results of other high schools in the district (see school summary for every school in the Per School Summary table in below Thomas High School segment). <br>
<br/>

* Thomas High School Performance:<br>
Replacing 9th grader scores with NaNs lower the overall Thomas High School academic results slightly.  The green box in the table below highlighted Thomas High School's performance before the score replacement data treatment.  One can compared these results to the overall Thomas High School performance after replacing 9th graders' scores shown below the summary table.     
<img src =  "Resources/Schools_w_Thomas_adj.png">
<br/>

* Other affect:<br/>

    *Math and reading scores by grade* - replacing Thomas High School 9th grader's scores has no impact to averages in all other high schools and grade.  The impact is isolated to only Thomas High School 9th grade as show in tables below.  Both of these averages are shown as NaN<br>
    <br/>
        <img src = "Resources/Scores_by_Grade.PNG" width="600px">
    <br/>

    *Scores by school spending* - We dividing the entire district into four spending bins for this analysis.  with rounding, there is no affect from replacing Thomas High School scores with Nans. <br/>
        <img src = "Resources/Scores_by_Spending.PNG" width= "450px">
        <br/>
    *Scores by school size* - We dividing the entire district into three size bins for this analysis.  with rounding, there is no affect from replacing Thomas High School scores with Nans.<br>
        <img src = "Resources/Scores_by_Size.PNG" width="450px">
    <br/>

    *Scores by school type* - We dividing the entire district into two type bins for this analysis.  with rounding, there is no affect from replacing Thomas High School scores with Nans.<br>
        <img src = "Resources/Scores_by_Type.PNG" width="450px">
    <br/>

## Summary


