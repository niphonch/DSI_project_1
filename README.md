# Project 1: Standardized Test Analysis: The Relationships Between ACT Score and State Educational Funding

### Problem Statement

The ACT (American College Testing) is one of the highest stake standardized tests used for high school graduation and college admission in the US. The test aims to measure educational development and readiness to pursue college-level coursework in English, Mathematics, Reading, and Science, with an additional optional writing section. (source: https://nces.ed.gov/fastfacts/display.asp?id=897). Approximately 2 million students take the test each year. However, the average test scores are dispersed widely from one state to another due to many factors. This study aims to analyze the relationships between ACT tests scores and state educational funding


### Data Dictionary

|Feature|Type|Dataset|Description|
|:--------|:------|:---------|:-------------|
|state|object|df/df_act/df_add|Sates in USA| 
|act19_participation|float|df/df_act| Students participation rate of 2019 ACT| 
|act19_composite|float|df/df_actT|2019 ACT composite score| 
|act18_participation|float|df/df_act| Students participation rate of 2018 ACT| 
|act18_composite|float|df/df_act|2019 ACT composite score| 
|funding_level|object|df/df_add|Funding level: determined by dividing state and local revenue by student enrollment. | 
|funding_dist |object|df/df_add|Funding distribution: do states provide more or less funding to
districts as the poverty rate increases?| 
|funding_effort|object|df/df_add| Funding effort: measured as total state and local revenue (including capital outlay and debt service.
excluding all federal funds) divided by the state’s gross domestic product (GDP).| 
|k12_spend |float|df/df_add| Public K-12 spending per pupil per year| 
|ranking |float|df/df_add| Overall education ranking| 
|college_ready_score|float|df/df_add|College readiness ranking| 


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
