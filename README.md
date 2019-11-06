# SAT & ACT Analysis

#### Kristina Joos, September 17, 2019

## Problem Statement

With the The No Child Left Behind Act of 2001, public schools were forced to administer annually statewide standardized testing
to their highschool students in order do receive funding.

Since many states recognized the pressure that 11 graders face because many of them are preparing for their college admission
tests, they decided to adopt one of the college admission tests as their statewide assessment test, and close a contract with either the College 
Board (SAT), or the ACT.

In the beginning, many states choose the ACT  over the SAT, since it closely aligned with the high school curriculum.
The number of ACT takers overtook t the number of SAT takers.
However, after the release of their revised SAT in 2016, the College Board is gaining traction and in 2019 2.1 Million students took the 
SAT, the highest number ever
(https://www.collegeboard.org/releases/2018/more-than-2-million-students-in-class-of-2018-took-sat-highest-ever) whereas the number of ACT takers dropped slightly to 1.9 (https://www.act.org/content/dam/act/unsecured/documents/cccr2018/National-CCCR-2018.pdf)

In this project, I will take a close look at SAT and ACT scores and participation rates for the year 2017 and 2018 in all States and 
Washington, D.C, and try to find the answer to the following question:

- Which test is the predominant test in each state?
- How are the outcomes of the tests in each state?
- Is there a correlation between participation rates in the tests and the test results?
- Is there a trend of states changing from one test to the other?

After I have gained a thorough understanding of the data, I will make a recommendation to the College Board, the nonprofit organization that is selling owning the SAT, how to gain an even higher market share.

## Used Data Sets
sat_2017
act_2017
sat_2018
act_2018

#### Data dicitionairy

##### 2017
|Feature|Type|Dataset|Description|
|---|---|---|---|
|State|object|ACT/SAT|The 51 States plus Washington DC|
|act_2017_paricipation|float|ACT|The ACT participation rate for each state in 2017 as decimal|
|act_2017_english|float|ACT|The average scores of the ACT's English section for each state|
|act_2017_math|float|ACT|The average scores of the ACT's Math section for each state|
|act_2017_reading|float|ACT|The average scores of the ACT's Reading section for each state|
|act_2017_science|float|ACT|The average scores of the ACT's Science section for each state|
|act_2017_composite|float|ACT|The average scores of the combined ACT sections for each state|
|sat_2017_participation|float|SAT|The SAT participation rate for each state in 2017 as decimal|
|sat_2017_erw|int|SAT|The average score of the SAT's evidence-based Reading & Writing section for each State|
|sat_2017_math|int|SAT|The average score of the SAT's Math section for each State|
|sat_2017_total|int|SAT|The total average score of the SAT for each State|


##### 2018
|Feature|Type|Dataset|Description|
|---|---|---|---|
|State|object|ACT/SAT|The 51 States plus Washington DC|
|act_2018_paricipation|float|ACT|The ACT participation rate for each state in 2017 as decimal|
|act_2018_composite|float|ACT|The average scores of the combined ACT sections for each state|
|sat_2018_participation|float|SAT|The SAT participation rate for each state in 2017 as decimal|
|sat_2018_erw|int|SAT|The average score of the SAT's evidence-based Reading & Writing section for each State|
|sat_2018_math|int|SAT|The average score of the SAT's Math section for each State|
|sat_2018_total|int|SAT|The total average score of the SAT for each State|


## Executive Summary
Contents:
2017 Data Import & Cleaning
2018 Data Import and Cleaning
Exploratory Data Analysis
Data Visualization
Descriptive and Inferential Statistics
Outside Research
Conclusions and Recommendations

## Findings

There is a clear trend of states switching from the ACT to the SAT between 2017 and 2018.
In Illinois and Colorado, the participation rate for the SAT increased by almost 90%.
The increase is due to the sates entering into contracts with the College Board to use the SAT for their yearly statewide assessment testing.
Only in Florida (-26%) and in DC (-7.5%) decreased the participation rate for the SAT from one year to another.

Presentation to the College Board:
Lately, more and more College retain from using standardized test for college admission. While the change in requirements poses a problem for the College Board, it is also an excellent opportunity to position the SAT in new ways; More and more states are adopting the SAT in their high schools for statewide standardized testing in the context of the NCLB assessments.
Entering into many year contracts with states provides security for the College Board.  It makes the SAT mandatory for all high school students, increasing the participation rates in this state to 100%.
There are also benefits for the states: All students can participate in the SAT no matter what their socio-economical background is. Since the SAT is a college readiness test, it is a good measurement of how well the curriculum of a state is doing in preparing students for College.
Also, for students who had already planned on taking the SAT, it eliminates the pressure of taking a second test by combining college admission testing with statewide assessment testing.
In addition, the College Board provides free SAT preparation materials for all students, helping students to prepare and improving the test outcomes. 

After analyzing the data, I found three groups of states: States that already have a contract with the SAT  States that already have a contract with the ACT States that don't have contracts yet.
 I decided to focus on the third group of states. 
It is reasonably straightforward to convince the state to switch from their momentarily statewide assessment testing (probably a less prevalent test, not recognized for college admission, maybe lower quality) to a highly appreciated standardized test that provides many benefits (college admission, free preparation material).

I think it is essential to secure contracts with states that have not decided on a test yet, and later focus on states that are already conducting ACT testing. 
 
I narrowed the undecided states down to states with participation rates in the SAT between 30 and 80% and higher SAT scores:
A decent part of students in these states are already taking the SAT, so it is familiar to everyone. That makes it easier to convince all stakeholders of the SAT as a statewide assessment test.
Going into contracts with states that already very high participation rates, even so, the test isn't mandatory, don't add a significant market share. The College Board should try to score contracts with these states as well, but for now, I focus on states that will add a considerable amount of test-takers if a contract is concluded.
Furthermore, I narrowed the number of possible states by their SAT scores. We can make the argument, that in states with already good SAT outcomes, the curriculums align well with what is demanded in the SAT. Therefore these states are more likely to have good results when they implement the SAT as a statewide assessment and don't run into problems with federal funding. 
I choose states where the SAT total score is 1100 or above (statewide average is 1120).

The following states match my criteria:
Virginia (8.5 Milion Residents / 98 000 students)
Massachusetts (7 Million Residents / 80 500 students)
Oregon (4 Million Residents / 46 000 students)
Alaska (740 000 Residents /  8510 students)
Vermont (630 000 Residents / 7250 students)

I recommend focussing on Virginia, Massachusetts, and Oregon since they would add the most test-takers.

Estimation for the percentage of the population being a highschool senior:
330 Milion Americans
3.8 Million High school graduates each year (https://nces.ed.gov/fastfacts/display.asp?id=372)
--> 1.15% of the population is a high school senior



