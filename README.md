# School_District_Analysis
## Overview of Analysis

- Maria has contracted us to assist with some data analysis for the school district grades. There is evidence of
academic dishonesty among 9th graders in Thomas High School. Maria has requested to have those scores removed from
the analysis as to not skew the averages with tainted data. We will be using Pandas and Python in Jupyter Notebook
to help Maria with this task.

### How is the district summary affected?

- Below you will see small change from district summary before removing Thomas HS 9th grade math and reading scores.

1. Average Math score dropped by .1
2. Average Reading score did not change
3. % Passing Reading dropped by .3%
4. % Passing Math dropped by .2%
5. % Overall Passing dropped by .1%

![alt text](https://github.com/brivasbravo/School_District_Analysis/blob/main/PyCitySchoolsOriginal.jpg)
![alt text](https://github.com/brivasbravo/School_District_Analysis/blob/main/PyCitySchoolsChallenge.jpg)

### How is the school summary affected?

- School summary is affected because can see the change under Thomas HS for both math and reading averages and % passing:

![alt text](https://github.com/brivasbravo/School_District_Analysis/blob/main/PyCitySchoolsOriginalB.jpg)
![alt text](https://github.com/brivasbravo/School_District_Analysis/blob/main/PyCitySchoolsChallengeB.jpg)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

This change severely affects relative performance because % passing math, reading, and overall are in the 60 showing a large portion are 
below passing at Thomas HS now.

### Math Scores by grade

Affect by grade is 9th graders math and reading changes to a 'nan' instead of a score:


![alt text](https://github.com/brivasbravo/School_District_Analysis/blob/main/PyCitySchoolsOriginalD.jpg)
![alt text](https://github.com/brivasbravo/School_District_Analysis/blob/main/PyCitySchoolsChallengeD.jpg)


![alt text](https://github.com/brivasbravo/School_District_Analysis/blob/main/PyCitySchoolsOriginalC.jpg)
![alt text](https://github.com/brivasbravo/School_District_Analysis/blob/main/PyCitySchoolsChallengeC.jpg)


### Scores by School spending

Scores by school spending was extremely minimal change. Formatted table would not show the
difference so the unformatted tables are used below to demonstrate the slightest change.
The average math score was lower by only .0017 and reading went up by .012 points. 
Math and reading passing % went down by .022 and .072 % and overall passing percent went down by .08%.
Changes all happened within $631-645 spending range row because Thomas HS is within this limit.


![alt text](https://github.com/brivasbravo/School_District_Analysis/blob/main/PyCitySchoolsOriginalE.jpg)
![alt text](https://github.com/brivasbravo/School_District_Analysis/blob/main/PyCitySchoolsChallengeE.jpg)


### Scores by School Size

Thomas HS is under the Medium (1000-1999) School Size so scores only changed for this row. Again very small difference
and unformatted version of table has to be used to note the difference. Average math score dropped by .01, average reading
up by .1, % Passing Math is down by .017%, % Passing Reading down by .06%, and % Overall Passing is down by .07%.

![alt text](https://github.com/brivasbravo/School_District_Analysis/blob/main/PyCitySchoolsOriginalF.jpg)
![alt text](https://github.com/brivasbravo/School_District_Analysis/blob/main/PyCitySchoolsChallengeF.jpg)


### Scores by School Type

We again see small difference and are required to use the unformatted table below for school type. Thomas HS
is classified as a Charter School so only affects this row. Average Math Scores down by .01, Average Reading Score
up by .01, % Passing Math down by .01%, % Passing Reading down by .03%, and % Overall Passing down by .04%.

![alt text](https://github.com/brivasbravo/School_District_Analysis/blob/main/PyCitySchoolsOriginalG.jpg)
![alt text](https://github.com/brivasbravo/School_District_Analysis/blob/main/PyCitySchoolsChallengeG.jpg)

### Summary

Changes were minimal throughout except for at the School level which plunged the Passing Math, Passing Reading and Overall Passing
% from the 90s to the 60s.











