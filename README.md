# School_District_Analysis

## Overview of Project
Analyzed standardized test data from a city school district in order to report on test performance trends and patterns based on school size, school budget, school type, and grade level. After analysis was completed, the ninth grade scores for Thomas High School were removed due to academic dishonesty and the following metrics were repeated with those scores taken out.

The following tables were provided to give a snapshot of the district's key metrics:

1. The average math score received by students in each grade level at each school
2. The average reading score received by students in each grade level at each school
3. Top 5 and bottom 5 performing schools, based on the overall passing rate 
4. School performance based on the budget per student
5. School performance based on the school size 
6. School performance based on the type of school

## Results

- How is the district summary affected?
  - The district summary is affected in four areas by the removal of Thomas High School's ninth grade scores. In these four areas, all of the scores decreased but they did not decrease by much. The average math score decreased from 79 to 78.9, the percentage passing math decreased from 75% to 74.8%, the percentage passing reading decreased from 86% to 85.7%, and the percentage overall passing decreased from 65% to 64.9%. The Average Reading Score is the only category that does not change.

- How is the school summary affected?
  - The school summary is affected by the removal of Thomas High School's ninth grade scores in five areas, but like the district summary these scores don't change by much. The average math score decreased from 83.41 to 83.35. The average reading score increased from 83.84 to 83.89. The percentage passing math decreased from %93.27 to %93.19. The percentage passing reading decreased from %97.31 to %97.02, and the percentage overall passing decreased from %90.95 to %90.63.

- How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?
  - Replacing the ninth graders' math and reading scores does not affect Thomas High School's performance relative to other schools that much. Their percentage passing overall does decrease slightly, but even with the ninth grade reading and math scores removed, Thomas High School still ranked second in the district for overall passing scores.

- How does replacing the ninth-grade scores affect the following:
	- Math and reading scores by grade
	  - The only math and reading scores by grade affected by replacing the ninth grade scores are the ninth grade scores from Thomas High School.
	- Scores by school spending
	  - Scores by school spending are not affected by replacing the ninth grade scores.
  - Scores by school size
	  - Scores by school size are not affected by replacing the ninth grade scores.
  - Scores by school type
	  - Scores by school type are not affected by replacing the ninth grade scores.

## Summary
After reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs, the school district analysis has changed in a few ways. The school district summary scores decrease in four areas, and the school summary scores for Thomas High School change in every area, with only the average reading score increasing. Thomas High School's scores don't change that much relative to other schools, and even with the small changes they still rank second for overall passing percentage.
