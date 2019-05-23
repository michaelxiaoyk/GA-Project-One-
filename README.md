## Problem Statement

Study and analyse trends in the data to find out what is affecting participation rates for ACT and SAT tests and how can this be improved.

## Executive Summary

In the USA, students are familiar with the ACT test and the SAT test. In this case, we will be using ACT and SAT data from 2017-2018, to understand and comment on participation rates and the different average scores for each test. We will explore changes and carry out external research to better understand what the data cannot explain. At the end, conclusions and recommendations will be made on how we can better improve on future participation rates of ACT and SAT tests. 

## Data Dictionary

|Feature|Type|Dataset|Description|
| :---: | :---: | :---: |:---:|
|state|object|ACT/SAT|Name of states across USA|
|act_17_participation|float|ACT (act_2017)|Percentage of participation rate for 2017 ACT test|
|act_17_english|float|ACT (act_2017)|ACT 2017 English average score|
|act_17_math|float|ACT (act_2017)|ACT 2017 Math average score|
|act_17_reading|float|ACT (act_2017)|ACT 2017 Reading average score|
|act_17_science|float|ACT (act_2017)|ACT 2017 Science average scoree|
|act_17_composite|float|ACT (act_2017)|ACT 2017 Composite score|
|sat_17_participation|float|SAT (sat_2017)|Percentage of participation rate for 2017 SAT test|
|sat_17_erw|int|SAT (sat_2017)|SAT 2017 Evidence-Based Reading and Writing average score|
|sat_17_math|int|SAT (sat_2017)|SAT 2017 Math average score|
|sat_17_total|int|SAT (sat_2017)|SAT 2017 Total score|
|act_18_participation|float|ACT (act_2018)|percentage of participation rate for 2018 ACT test|
|act_18_english|float|ACT (act_2018)|ACT 2018 English average score|
|act_18_math|float|ACT (act_2018)|ACT 2018 Math average score|
|act_18_reading|float|ACT (act_2018)|ACT 2018 Reading average score|
|act_18_science|float|ACT (act_2018)|ACT 2018 Science average score|
|act_18_composite|float|ACT (act_2018)|ACT 2018 Composite score|
|sat_18_participation|float|SAT (sat_2018)|Percentage of participation rate for 2018 SAT test|
|sat_18_erw|int|SAT (sat_2018)|SAT 2018 Evidence-Based Reading and Writing average score|
|sat_18_math|int|SAT (sat_2018)|SAT 2018 Math average score|
|sat_18_total|int|SAT (sat_2018)|SAT 2018 Total score|
|sat_participation_change|float|SAT (final)|2017-2018 SAT participation rate change|
|act_participation_change|float|ACT (final)|2017-2018 ACT participation rate change|

### Key Takeaways
- Different states in America have different test requirements for their students (not standardised).
  - ACT and SAT participation rate share an inverse relationship. 
  - Consistent from what we found in 'Outside Research'. Recent news seem to suggest certain states are recognising SAT more so than ACT and have implemented a change in state requirement for juniors. 
  - Bimodal distribution in the histograms. As bimodal distribution often suggest that there are 2 groups, we can think of the distribution as:
    - states that require SAT
    - states that require ACT
- States have to consider a smooth transition from one test requirement to another.
   - Among concerns of inconsistent scoring, states such as Colorado and Illinois have since used SAT as their main requirement for juniors. 
   - The transition was abrupt, occuring in the mid of the school term. This means that transitioned students may not have enough time to adequately prepare themselves for the SAT and have resulted in poorer grades. 
   - The scatterplot between Participation vs Total/Composite Scores show that the higher the participation rate, the poorer the score (inverse relationship). 
   - This suggests that the former argument holds certain truth but it also means that states that did not make any transition tend to fare better in test.
- Other factors may be affecting certain states who have consistently poor participation rates.
   - In our data, they were many states that had consistent participation rates as well. Some of these states however face consistently poor participation rates as well. 
   - This is similar to the 'Estimates Limits of Data' where reasons may not be found within our data. States with much less population may seem to 'contribute' much less to the national average. 
   - This can also lead to other factors such as poor learning environment or lack of schools which might possibly lead to students not being able to prepare themselves for the test.

### Recommendation

###### Alabama 
|Participation|Percentage|
|---|---|
|act_17_participation|0.08 (8%)|
|act_18_participation|0.07 (7%)|      
|sat_17_participation|0.02 (2%)| 
|sat_18_participation|0.02 (2%)|

States that show changes within SAT or ACT participation rates may be due to points 1 and 2 in Key takeaways. As such we focus on Alabama, the state with the lowest ACT/SAT participation rates in the USA. 

Background on Alabama's educational attainment: https://cber.cba.ua.edu/rbriefs/ab2003Q2_education.pdf

Although education/educational attainment has improved over the years, it is vital for the newer generation to understand the importance of education in the long run. I will recommend the College Board to take on a more holistic approach towards education for states like Alabama and alike; to get current students (graduating seniors) to understand how pursuing education may help them progress farther as compared to being in the working class. 
