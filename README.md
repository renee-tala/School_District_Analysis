# PyCity Schools: School District Analysis

## Overview of the Analysis
You are working for a school board analyzing students grades at Thomas High School. There is evidence of academic dishonesty, so your supervisor wants you to remove ninth grader's reading and math grades at Thomas High School. Once you've removed and replaced the data with NaNs, conduct the distrcit summary and school summary again. 
- You will also show:
  - The top 5 and bottom 5 performing schools
  - The average math score for each grade level for each school
  - The average reading score for each grade level for each school
  - The scores by:
    - school spending per student
    - school size
    - school type

- Resources:
  - Jupyter Notebook, Pandas Library, Python
  - schools_complete.csv and students_complete.csv 


## Results

* Math and reading scores by grade before replace ninth grade scores:
  ![originalscores](avg_original.png)
* Math and reading scores by grade after replacing ninth grade scores:
  ![no_ninth](avg_no_ninth_ths.png)
  * As you can see, Thomas High School's percentage of passing has gone down without the ninth grade class. 
  * The percentage passing math went from 93.3% to 66.9%
  * The percentage passing reading went from 97.3% to 69.6%.
  * The overall passing percentage went from 90.9% to 65.1%.

- The following three images show district scores based on spending, size, and type. 
    - Scores by school spending
    ![schoolspending](scores_by_school_spending.png) 
    - School spending has been split into four ranges. This was determined by calculating the amount each school spends per student and then split into four groups as evenly as possible. 
    - Scores by school size
    ![schoolsize](scores_by_school_size.png)
    - Splitting the school size into three groups was determined by the amount of students per school and the number of schools there are. 
    - Scores by school type
    ![schooltype](scores_by_school_type.png)
    - There are two types of schools already categorized for us. 
    
## Summary
- This analysis shows that:
  - Thomas High School's averages in grades plummets after removing the ninth grader's scores. 
  - Therefore, Thomas High School lost its place as one of the top five schools in the District.
  - We cannot determine whether or not academic dishonesty truly took place using this analysis. Removing an entire grade level from a school within a district would result in a major difference in the school summary and district summart, regardless of plagarism or cheating.
