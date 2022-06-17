# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Test Analysis

## Problem Statement

High school students preparing for college are typically getting ready to take the SAT, and many don’t know what score to aim for and whether it may be worth it to retake it. This project aims to identify any correlation between SAT score and admittance rates, and any other trends within the previous years SAT scores.

## Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|*object*|sat_2017, sat_2018, sat_2019|The state in which the scores are coming from.|
|**participation_2017**|*float*|sat_2017|The percent of participation for each state in the SAT in 2017.|
|**ebrw_2017**|*int*|sat_2017|The SAT Evidence-Based Reading and Writing Score for each state in 2017.|
|**math_2017**|*int*|sat_2017|The SAT Math Score for each state in 2017.|
|**total_score_2017**|*int*|sat_2017|The total SAT score for each state in 2017.|
|**participation_2018**|*float*|sat_2018|The percent of participation for each state in the SAT in 2018.|
|**ebrw_2018**|*int*|sat_2018|The SAT Evidence-Based Reading and Writing Score for each state in 2018.|
|**math_2018**|*int*|sat_2018|The SAT Math Score for each state in 2018.|
|**total_score_2018**|*int*|sat_2018|The total SAT score for each state in 2018.|
|**participation_2019**|*float*|sat_2019|The percent of participation for each state in the SAT in 2019.|
|**ebrw_2019**|*int*|sat_2019|The SAT Evidence-Based Reading and Writing Score for each state in 2019.|
|**math_2019**|*int*|sat_2019|The SAT Math Score for each state in 2019.|
|**total_score_2019**|*int*|sat_2019|The total SAT score for each state in 2019.|
|**intended_college_major**|*object*|sat_2019_by_intended_college_major|The intended college major for SAT test takers in 2019.|
|**test_takers**|*int*|sat_2019_by_intended_college_major|The amount of SAT test takers in 2019 for each respective intended college major.|
|**percent**|*float*|sat_2019_by_intended_college_major|The percent of total SAT test takers in 2019 for each respective intended college major.|
|**total_score**|*int*|sat_2019_by_intended_college_major|The total SAT score for each respective intended college major in 2019.|
|**read_write**|*int*|sat_2019_by_intended_college_major|The SAT Evidence-Based Reading and Writing Score for each respective intended college major in 2019.|
|**math**|*int*|sat_2019_by_intended_college_major|The SAT Math score for each respective intended college major in 2019.|
|**year**|*int*|sat_2019_by_intended_college_major|The year that these SAT scores were obtained, 2019.|
|**school**|*object*|sat_act_by_college|The respective school where the recent SAT and acceptance rates are coming from.|
|**number_applicants**|*int*|sat_act_by_college|The number of applicants for these schools.|
|**accept_rate**|*float*|sat_act_by_college|The acceptance rate for these schools.|
|**sat_25_percentile**|*float*|sat_act_by_college|The 25th percentile for the SAT scores.|
|**sat_75_percentile**|*float*|sat_act_by_college|The 75th percentile for the SAT scores.|


## Summary of Analysis

I first looked at the participation rates for 2017-2019 and total SAT score for those same years to see if I could spot any trends. Then I delved into the SAT scores by major to see if anything there stood out for my problem statement. Lastly, I went through the SAT scores by college data set and found some interesting correlations there.

## Conclusions/Recommendations

Based on my exploration of the data, the key takeaways I discovered were that SAT participation rates were mostly consistent between 2017-2019 with the exception of a few states, participation rates were negatively correlated with total SAT scores (as participation rates increased, total scores decreased), and the recent total SAT scores had a negative correlation with recent acceptance rates. 

Based on those key takeaways, it appears that a higher total SAT score doesn’t necessarily give someone an advantage for getting into college. Of course, this does also depend on what college students are primarily aiming for, such as Ivy League. But overall, my recommendation is that colleges shouldn’t put as much emphasis on SAT standardized test scores for what makes a good candidate. There are many other aspects of a student’s qualifications that could make them an excellent candidate for said school.

For further analysis, I’d love to explore the reasons for the negative correlation between SAT total score and college acceptance rates. There could be many factors, but I didn’t get a chance to look into those this time around.
