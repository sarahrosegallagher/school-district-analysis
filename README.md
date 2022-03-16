# School District Analysis
## Overview of the school district analysis: 

This analysis generated dataframes using test data to inform school board decision making. There were two phases to this analysis: first, with complete data for all students from the included high schools and then, with select data excluded based on evidence of academic dishonesty. 

The code for the first phase analysis can be found in PyCitySchools_Initial_Analysis. The first step was to explore and clean the data. Then I generated the first, overarching school district summary (calculating the number of students, number of schools, the total budget, test score averages, passing percentages). I also generated additional data frames: a summary for each school, high and low performing schools, average math and reading scores by grade, scores grouped school spending per student, scores grouped by school size, and scores grouped by school type. 

The second analysis required replacing the ninth grade scores for Thomas High School with null values and then re-runing the school district analysis based on the modified data. This code can be found in PyCitySchools_Challenge. 

## Tools:
* Python 3.10.2
* VS Code 1.65.0
* Pandas
* NumPy

## Results: 

### How is the district summary affected?

![initial district summary](/Resources/initial_district_summary.png)

![challenge district summary](/Resources/challenge_district_summary.png)


### How is the school summary affected?

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

### How does replacing the ninth-grade scores affect the following:

* Math and reading scores by grade

* Scores by school spending

* Scores by school size

* Scores by school type

## Summary: 

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
