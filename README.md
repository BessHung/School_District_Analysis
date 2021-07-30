# School District Analysis

## Project Overview
The purpose of this project is to analyze student funding and standardized test scores and showcase school performance for the school board in making decision on school budget and priorities. 
However, the school board has notified that the file shows evidence of academic dishonesty. Specifically, reading and math grades for Thomas High School ninth graders. Therefore, the report needs to be modified by replacing those data with “NaN” and recreate the following metrics:

-	The district summary
-	The school summary
-	Top 5 and bottom 5 performing schools, based on the overall passing rate
-	The average math score received by students in each grade level at each school
-	The average reading score received by students in each grade level at each school
-	School performance based on the budget per student
-	School performance based on the school size 
-	School performance based on the type of school

## Results
Due to the academic dishonesty issue, all the ninth-grade reading and math scores at Thomas High School have been replaced by “NAN”.  Thus, the data for reviewing school performance have been recalculated. Comparing with the original results, here are the effects of the new analysis.

- #### District summary
There is total 491 number of students in 9th grade at Thomas High School, which is 1.25% of entire data. After excluding those data, as we can see from the screenshots, the average math and reading score are almost the same, and the “% Passing Math”, “% Passing Reading” and “% Overall Passing” are drop around 0.1% to 0.3%.

###### Original district summary 
![](https://github.com/BessHung/School_District_Analysis/blob/158fd1bb78402b63631e95c09dfd11d52290bbb1/Resources/District%20summary_original.png)
###### Revised district summary 
![](https://github.com/BessHung/School_District_Analysis/blob/31902f7ae327f1270577eae65eeb5c2e18c369b3/Resources/District%20summary_modified.png)

- #### School summary
9th grade Thomas High School data have been excluded when recalculating the summary scores by school. The average and percentage results showing in the screenshot below are going down. It indicates that the performance of the students in 9th grade are above the average in Thomas High School with original data. Besides, there are no changes to the other schools.
###### Original THS summary 
![](https://github.com/BessHung/School_District_Analysis/blob/bb1d7c1c94f3e5fed306fa5bd65d25e59205ea65/Resources/THS%20summary_original.png)
###### Revised THS summary
![](https://github.com/BessHung/School_District_Analysis/blob/31902f7ae327f1270577eae65eeb5c2e18c369b3/Resources/THS%20summary_modified.png)

- #### School ranking
The school ranking is determine by the percentage of overall passing. Althouge the performance from Thomas High School is dropping slightly after recalculating, its ranking is still remaining in the 2nd place. Moreover, in the top 5 school, it is just less than 0.1% difference between the 2nd place and the 5th place, which means that the school ranking could be changed if there are any issues happened again.

###### Top 5 school 
![](https://github.com/BessHung/School_District_Analysis/blob/dd1734a29e5b7f506e89fab9346e1acd3252a550/Resources/Top5_modified.png)
###### Bottom 5 school
![](https://github.com/BessHung/School_District_Analysis/blob/dd1734a29e5b7f506e89fab9346e1acd3252a550/Resources/Bottom5_modified.png)

- #### Math and reading scores by grade
Since the results are grouping by each school, the math and reading scores by grade tables didn't change except for 9th grade Thomas High School data, which value have been replaced with "NAN".
###### Math scores by grade and Reading scores by grade
![](https://github.com/BessHung/School_District_Analysis/blob/8af462129d2c1c18cadcdb6d56fab8f8625d345a/Resources/Math%20scores%20by%20grade_modified.png)
![](https://github.com/BessHung/School_District_Analysis/blob/8af462129d2c1c18cadcdb6d56fab8f8625d345a/Resources/Reading%20scores%20by%20grade_modified.png)
- #### Scores by school spending

![](https://github.com/BessHung/School_District_Analysis/blob/8af462129d2c1c18cadcdb6d56fab8f8625d345a/Resources/Scores%20by%20School%20Spending_modified.png)
- #### Scores by school size

![](https://github.com/BessHung/School_District_Analysis/blob/8af462129d2c1c18cadcdb6d56fab8f8625d345a/Resources/Scores%20by%20School%20Size_modified.png)
- #### Scores by school type

![](https://github.com/BessHung/School_District_Analysis/blob/8af462129d2c1c18cadcdb6d56fab8f8625d345a/Resources/Scores%20by%20School%20Type_modified.png)
## Summary
