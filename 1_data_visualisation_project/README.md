# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Testing, Statistical Summaries and Inference

### Gladys Pao, SG-DSI-17
### Project 1: SAT and ACT Analysis

### Sources of Data

The data used for this project are from the following sources: 
[SAT (2017)](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/),
[SAT (2018)](https://reports.collegeboard.org/sat-suite-program-results/state-results),
[ACT (2017)](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows),
[ACT (2018)](http://www.act.org/content/dam/act/unsecured/documents/cccr2018/Average-Scores-by-State.pdf)

### Problem Statement

Participation rates for college admission examinations in the United States (US), such as the SAT and ACT, have been increasing in recent years. However, the participation rates of the ACT has surpassed that of the SAT for many states in the US, with ACT being the market leader since 2012. With the ACT's ever-increasing popularity and more colleges going test-optional, increasing the participation rates of the SAT has been one of the issues that is being emphasised by the SAT's College Board, as supported by the College Board coming up with a new and improved version of the SAT on 2016 to tackle against the popular ACT. To gain a fuller understanding on the trends and factors influencing participation rates of the SAT in the US, an analysis of various states in the US regarding the following has been made:

- the participation rates of each state
- the SAT and ACT scores of each state
- the education policies of each state
- any other policies (e.g. subsidies) implemented with regards to college admission exams in each state

With insights made from these analyses, this project aims to suggest a suitable state and recommend actions to be taken to improve the state's SAT participation rate moving forward.

### Executive Summary

This project examines data that covers the participation rates and scores of students for the SAT and ACT exams in the United States (US). With the data organised at the state-level, participation rates, component scores and total or composite scores of each exam are provided for the years, 2017 and 2018. Through the use of these data, a state-by-state comparison and analysis of participation rates and scores of each exam is made, with insights derived from the analysis to help find out the trends and factors influencing participation rates in various US states.

Results of data analysed show that mandatory testing in any state causes a high participation rate for the mandatory test. Making a test mandatory also decreases participation in the other test significantly. Furthermore, a negative relationship between participation rates and its average test score also seems to be present at first glance due to selection bias, with states having a tendency to have higher average scores for both exams if their participation rates are lower. Through outside research, it has also been discovered that several states in the US, such as West Virginia, have a huge group of low-income students who have not been able to utilise the SAT subsidies to undertake the exam, hence overall affecting the participation rates in those states. Lastly, coastal states with no mandatory testing requirements in the U.S. have a higher preference for the SAT than the ACT.

With various analyses made on the data of the participation rates and scores of the SAT and ACT, a suitable state, California, is selected because it is deemed to have high potential for an increase in its SAT participation rate. This is followed by recommendations to increase the SAT participation rate for the state of California:

- negotiating a contract with California's State Board of Education for mandatory SAT testing
- implementing SAT School Day that provides free testing to students on a school day
- improving subsidies for lower-income students in the state of California

### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|ACT/SAT|The name of the respective state|
|sat_2017_participation|float|SAT|The statewide percentage of students who participated in 2017's SAT (presented to two decimal places; 0.38 mean 38.0%)|
|sat_2017_reading_writing|integer|SAT|The state average score of the Evidence-Based Reading and Writing section for the 2017's SAT |
|sat_2017_math|integer|SAT|The state average score of the Math section for the 2017's SAT|
|sat_2017_total_scores|integer|SAT|The state average total score for the 2017's SAT|
|act_2017_participation|float|ACT|The statewide percentage of students who participated in 2017's ACT (presented to two decimal places; 0.60 mean 60.0%)|
|act_2017_english|float|ACT|The state average score of the English section for the 2017's ACT|
|act_2017_math|float|ACT|The state average score of the Math section for the 2017's ACT|
|act_2017_reading|float|ACT|The state average score of the Reading section for the 2017's ACT|
|act_2017_science|float|ACT|The state average score of the Science section for the 2017's ACT|
|act_2017_composite|float|ACT|The state average score of all sections (English, Math, Reading and Science) for the 2017's ACT|
|sat_2018_participation|float|SAT|The statewide percentage of students who participated in 2018's SATs (presented to two decimal places; 0.38 mean 38.0%)|
|sat_2018_reading_writing|integer|SAT|The state average score of the Evidence-Based Reading and Writing section for the 2018's SAT| 
|sat_2018_math|integer|SAT|The state average score of the Math section for the 2018's SAT| 
|sat_2018_total_scores|integer|SAT|The state average total score for the 2018's SAT|
|act_2018_participation|float|ACT|The statewide percentage of students who participated in 2017's ACT (presented to two decimal places; 0.60 mean 60.0%)| 
|act_2018_english|float|ACT|The state average score of the English section for the 2018's ACT|
|act_2018_math|float|ACT|The state average score of the Math section for the 2018's ACT|
|act_2018_reading|float|ACT|The state average score of the Reading section for the 2018's ACT|
|act_2018_science|float|ACT|The state average score of the Science section for the 2018's ACT|
|act_2018_composite|float|ACT|The state average score of all sections (English, Math, Reading and Science) for the 2018's ACT|
|sat_participation_change|float|SAT|The state change in participation rate for SAT from 2017 to 2018 (presented to two decimal places; 0.38 mean 38.0%)|
|act_participation_change|float|ACT|The state change in participation rate for ACT from 2017 to 2018 (presented to two decimal places; 0.38 mean 38.0%)|

### Takeaways

The following takeaways can be made from all the analyses made:
1. The ACT and SAT participation distributions roughly mirror each other, with most states preferring one test to the other. 
2. ACT appears to have a stronger foothold on more states in the U.S., with drastically higher number of states achieving full participation rates as compared to that of the SAT.
3. Higher participation rates in one particular test usually means low participation in another.
4. Huge increases in participation for a particular test usually comes from statewide test-taking changes, such as mandatory testing.
5. Participation rates appears to be negatively correlated with test scores due to selection bias.
6. Test scores remained relatively similar during both 2017 and 2018; the states that scored the highest or lowest test scores also remained largely similar.
7. Coastal US states that have no mandatory testing requirements tend to prefer the SAT over the ACT.

### Conclusion and Recommendations

The state chosen to improve its participation rate is California, a coastal US state which currently does not have any mandatory SAT or ACT testing requirements, and has a fairly low SAT participation rate that is below the 50th percentile. It also has the third least high school graduates in the U.S., as well as a huge lower-income student population, with close to 70% of the student population coming from lower-income families in 45 school districts located in California.

#### Recommendations

<b>State's education board policy changes</b><br>
Making the SAT a mandatory test is one of the biggest factors to boosting the SAT participation rate greatly. This can be seen in the state of Colorado and Illinois, where mandatory testing helped to increase the participation rates greatly with 89% in 2018 for Colorado, and a 90% increase for Illinois. The College Board should negotiate a contract with California's State Board of Education to help implement a mandatory state assessment using the SAT. Without any current mandatory test required for their test-takers, it will be easier for the College Board to negotiate statewide contracts for administration of the SAT for California. 

Contracts signed with the board should also be long-term, so as to maintain a high participation rate for a longer period of time. This is supported by the case of Connecticut, where its long-term mandatory SAT assessment has helped the state to achieve full participation rates for both 2017 and 2018.

<b>SAT School Day </b><br>
The implementation of SAT School Day has also helped to boost the SAT participation rate for a state, especially with the mandatory implementation of SAT testing for test-takers in the state. Implementing SAT School day in the state of California is definitely beneficial in increasing the participation rate for the state, especially for the huge number of low-income students living in California.
Allowing students to take the exam for free on a weekday has been proven to improve SAT participation rates, which can be seen in both Colorado and Illionois, and even West Virginia and Connecticut in which the implementation of SAT School Day was one of the factors that helped to secure higher SAT participation rates.

<b>More extensive subsidies with better student identification process:</b> <br>
More extensive fee waivers or subsidies should be provided to the lower-income students in the state of California for both the test and its retakes, especially since exam fees can present as an undue burden for this group of people. With the third lowest high school graduates and a large student lower-income student population in California, this means that graduating high school may be considered an impossible feat for most people in lower-income families without fee waivers. 

Steps taken to identify eligible students should also be improved so that more students can benefit from the subsidies. With more lower-income students being able to take the SAT (including retakes), the participation rate will definitely improve with higher percentages of students from lower-income families being able to afford the SAT through subsidies.

<b> Additional data </b><br>
The following additional data could be helpful:
- The demographic data (population, age, race, income levels) of each state, its cities, and its school districts 
- The submission rates of each type of exam (SAT and ACT) from various universities in the US
- The percentage of lower-income students in each state

Further research into the aforementioned data would be helpful in any further analysis and investigations moving forward.