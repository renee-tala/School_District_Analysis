# School District Analysis
- A high-level snapshot of the district's key metrics, presented in a table format
- An overview of the key metrics for each school, presented in a table format
- Tables presenting each of the following metrics:
    - Top 5 and bottom 5 performing schools, based on the overall passing rate
    - The average math score received by students in each grade level at each school
    - The average reading score received by students in each grade level at each school
    - School performance based on the budget per student
    - School performance based on the school size 
    - School performance based on the type of school
## Overview of the school district analysis
We are analysizing a school district's metrics using Jupter Notebook and Pandas.

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

How is the district summary affected?
How is the school summary affected?
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade

-The following three images show district scores based on spending, size, and type. 
    - Scores by school spending
    ![schoolspending](scores_by_school_spending.png)
    
    School spending has been split into four ranges. This was determined by calculating the amount each school spends per student and then split into four groups as evenly as possible. 
    
    - Scores by school size
    ![schoolsize](scores_by_school_size.png)
    
    Splitting the school size into three groups was determined by the amount of students per school and the number of schools there are. 
    
    - Scores by school type
    ![schooltype](scores_by_school_type.png)
    
    There are two types of schools already categorized for us. 
    
## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
