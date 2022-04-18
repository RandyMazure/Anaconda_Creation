# School District Analysis

## Project Overview
Maria, a chief data analyst for a school district, asked for assistance to analyze student funding test scores after academic dishonesty was discovered in one of the districts high schools.  The following tasks were assigned:

  - Recreate district/school summary DataFrames.
  - Recalculate the top and bottom five performing schools.
  - Recalculate average math scores received by students in each grade level at each school.
  - Recalculate average reading scores received by students in each grade level at each school.
  - Recalculate the school performance based on the spending per student.
  - Recalculate the school performance based on the size of the school.
  - Recalculate the school performance based on the type of school.

## Resources
- Data Source: schools_complete.csv, students_complete.csv
- Software: Python 3.10, Anaconda Navigator 4.10, Jupyter Notebook 6.4.5

## Results
How is the district summary affected?
  - The average math and reading scores remained the same
  - The % passing math and reading scores remained the same
  - The % overall passing increased from 54% to 74% in district schools
  - The % overall passing increased from 90% to 95% in charter schools
  
How is the school summary affected?
  - The only change was in Thomas High school
    - Average math scores for Thomas High School decreased from 83.42% to 83.35% 
    - Average reading scores for Thomas High School increased from 83.85% to 83.90%
    - The % passing math for Thomas High School decreased from 93.27% to 93.19%
    - The % passing reading for Thomas High school decreased from 97.31% to 97.02%
    - The % overall passing for Thomas High school decreased from 90.95% to 90.63%
    
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - Thomas High School ranked 2nd in overall passing % both before and after the ninth grade scores were stricken


How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
    - Unchanged overall except that Thomas High School no longer has any data for 9th grade
  - Scores by school spending
    - Unchanged except for increases in overall passing % across all bins:
    - < $586 increase from 90% to 95%
    - $586-$630 increase from 81% to 90%
    - $631-$645 increase from 63% to 79%
    - $646-$675 increase from 54% to 74%  
  - Scores by school size
    - Overall passing % changed for all sizes
    - Small increased from 90% to 95%
    - Medium increased from 91% to 95%
    - Large increased from 58 to 76%   
  - Scores by school type
    - Overall passing % for charter changed from 90% to 95%
    - Overall passing % for district changed from 54% to 74%
    
## Summary
By deleting all of the 9th grade data from Thomas High School, it had an impact on the overall passing % across all categories.  
