# School District Analysis<br>

## Overview of the school district analysis:<br>
Using tools in the Pandas library, we analyzed the PyCity school district’s school and student academic data. The analysis look at whether there is a correlation between academic performance and school funding, size, and type. We then look at if the academic data of Thomas High School's ninth-graders contain any signs of academic dishonesty by replacing the scores in question with NaNs in our analysis. 

## Results:

* District Summary:<br>
Replacing scores of Thomas High School's 9th graders with NaNs resulted in a slightly lower academic passing rate for the district. For math, it lowered from 75% to 74.8%. For reading, it lowered from 85.8% to 85.7%. This also resulted in a lower overall passing rate from 65.2% to 64.9%.<br>

<img src="Resources/District_Summary_Compare.PNG"><br>
<br>

* School Summary:<br>
Replacing the scores of Thomas High School 9th graders has no effect on the results of other high schools in the district (see school summary for every school in the Per School Summary table below Thomas High School segment). <br>
<br/>

* Thomas High School Performance:<br>
Replacing 9th grader scores with NaNs lowers the overall Thomas High School academic results slightly. The green box highlights Thomas High School's performance before the score replacement data treatment. One can compare these results to the overall Thomas High School performance after replacing 9th graders' scores in the summary below the table.<br>

<img src =  "Resources/Schools_w_Thomas_adj.png">
<br/>

* Other affect:<br/>

    *Math and reading scores by grade* - replacing Thomas High School 9th graders' scores has no impact on the averages in all other high schools and grades. The impact is isolated to only Thomas High School 9th grade as shown in the tables below. Both of these averages are shown as “nan”.<br>
    <br>
        <img src = "Resources/Scores_by_Grade.PNG" width="600px">
    <br/>

    *Scores by school spending* - We divided the entire district into four spending bins for this analysis. with rounding, there is no effect from replacing Thomas High School scores with Nans. <br/>
        <img src = "Resources/Scores_by_Spending.PNG" width= "500px">
        <br/>

    *Scores by school size* - We divided the entire district into three size bins for this analysis.  with rounding, there is no effect from replacing Thomas High School scores with Nans.<br>
        <img src = "Resources/Scores_by_Size.PNG" width="500px">
    <br/>

    *Scores by school type* - We divided the entire district into two type bins for this analysis.  with rounding, there is no effect from replacing Thomas High School scores with Nans.<br>
        <img src = "Resources/Scores_by_Type.PNG" width="500px">
    <br/>

## Summary
From this analysis we can see when we replace Thomas High School's 9th-grade reading and math scores with NaNs, it affected the five academic performance metrics we look at in our analyses.

The five academic performance metrics are average math score, average reading score, % passing math, % passing reading, and % overall passing.

These five performance metrics were affected in our district-level analysis. These effects also show up in the School level analysis. The impact would also be carried into our analysis of scores by school spending, size, and type.  Since we cannot detect any of these effects after rounding, we can conclude that we cannot detect any sign of academic dishonesty by way of lack of data anomaly.  

