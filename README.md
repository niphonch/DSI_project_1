# Project 1: Standardized Test Analysis: The Relationships Between ACT Score and State Educational Funding

### Problem Statement

The ACT (American College Testing) is one of the highest stake standardized tests used for high school graduation and college admission in the US. The test aims to measure educational development and readiness to pursue college-level coursework in English, Mathematics, Reading, and Science, with an additional optional writing section. (source: https://nces.ed.gov/fastfacts/display.asp?id=897). Approximately 2 million students take the test each year. However, the average test scores are dispersed widely from one state to another due to many factors. This study aims to analyze the relationships between ACT tests scores and state educational funding


### Data Dictionary

|Feature|Type|Dataset|Description|
|:--------|:------|:---------|:-------------|
|state|object|total_act_18_19|Sates in USA| 
|act19_participation|float|total_act_18_19| Students participation rate of 2019 ACT| 
|act19_composite|float|total_act_18_19|2019 ACT composite score| 
|act18_participation|float|total_act_18_19| Students participation rate of 2018 ACT| 
|act18_composite|float|total_act_18_19|2019 ACT composite score| 
|funding_level|object|total_act_18_19|Funding level: the cost-adjusted, per-pupil revenue from state and local sources | 
|funding_dist |object|total_act_18_19|Funding distribution: the extent to which additional funds are distributed to school districts with high levels of student poverty| 
|funding_effort|object|total_act_18_19| Funding effort: the level of investment in K-12 public education as a percentage of state wealth (GDP) allocated to maintain and support the state school system.| 
|k12_spend |float|total_act_18_19| Public K-12 spending per pupil per year| 
|ranking |float|total_act_18_19| Overall education ranking| 
|college_ready_score|float|total_act_18_19|College readiness ranking| 


### Analysis

1. Import data and data clean up.
2. Calculate simple statistics.
3. Generate correlation matrix
4. Explore data statistics by funding groups
5. Visualize data 
6. Interpret the results


### Conclusion and recommendation

   The aims of this study is to analyze the relationships between ACT tests scores and state educational funding. The results show that the public K-12 spending per pupil are moderately correlated with both 2018 and 2019 ACT composite scores, meaning the higher States allocate their budget to support K-12 education, the higher average ACT scores. Furthermore, the States which have higher grade in funding distribution have higher average ACT scores, while the other aspects of funding (funding level and funding effort) tend to produce relatively small to no difference in average ACT scores.
     Thus, we recommend the States and school administrators who are responsible for school budget planning to 
1.	Increase budget spending per pupil. 
2.	Strategically allocate spending to help low-achieving students and students who are in poverty.

      The results also show that Utha has the lowest public K-12 spending per pupil among the group, however, it's average ACT scores are relatively high. While Minesota has relatively high public K-12 spending per pupil, however, it's average ACT scores are the highest among the group. This highlights the needs of a more in-depth analysis of Utha and Minesota educational management and funding in the future. 


### Reference 

1. Making the grade 2019 extracted from How Fair is School Funding in Your State? (https://edlawcenter.org/research/making-the-grade-2019.html)

2. Public Educational Spending Per Pupil extracted from U.S. Public Education Spending Statistics (https://educationdata.org/public-education-spending-statistics)

3. Pre-K - 12 Rankings extracted from Measuring how well states are preparing students for college (https://www.usnews.com/news/best-states/rankings/education/prek-12)
