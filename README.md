# School District Analysis

## Project Overview
[1 sentence] 

### Purpose
1. Clean student names.
2. Calculate a district-wide summary.
3. Calculate average scores and passing rates for each school.
4. Identify the top and bottom 5 performing schools.
5. Calculate average scores for schools in different ranges of spending per student.
6. Calculate average scores for schools based on size range.
7. Calculate average scores for schools based on type.


### Resources
 - Data Sources: Resources/schools_complete.csv
                          /students_complete.csv
 - Software: Python 3.6.1, Jupyter Notebook

## Challenge Overview 
The challenge is meant to address possible academic dishonesty regarding the math and reading scores for 9th graders at Thomas High School.

### Challenge Purpose
Addressing the possible academic dishonesty only affects the math and reading scores for Thomas High School 9th graders; no other high school, grade, or score is affected. 
![thomas_9th](https://user-images.githubusercontent.com/90879979/137646354-e82eb442-9399-4004-af5f-890f4a2ba34e.png)




### Challenge Results
- The school district summary includes the updated average scores, which only minimally reduces the outcomes regarding math scores.
![District_summaries](https://user-images.githubusercontent.com/90879979/137646358-66269a1d-d648-45cb-a03a-3b6ae608df18.png)
- Only the average scores for Thomas High School are affected. The average scores change only within 0.10%.
![school_summaries](https://user-images.githubusercontent.com/90879979/137646364-8630ef52-8050-4282-9ff6-15539362b075.png)

- Replacing the 9th grade math and reading scores did not noticeably affect the average scores based on school size, type, or spending per student.

![by_school_size](https://user-images.githubusercontent.com/90879979/137646370-e34d88cc-7514-4801-aea1-a0702931459f.png)
![by_school_type](https://user-images.githubusercontent.com/90879979/137646372-ac476cc7-ed6b-4f4b-8370-6e39870863c6.png)
![by_school_spending](https://user-images.githubusercontent.com/90879979/137646374-95ec7eb8-7d16-471b-b393-d3b2f1fff3a5.png)


## Summary
 - This analysis illustrates average scores and overall performance for schools based on grade level, school size, spending, and type. 
 - Results that were potentially unreliable were replaced.
 - The reading and math scores and averages for 10th - 12th graders at Thomas High School are adjusted to account for the reduced student count.

![adjusted_student_count](https://user-images.githubusercontent.com/90879979/137646379-20edcf21-eedd-4881-aefe-571d4cdbdd56.png)
 - Thomas High School remained the second highest performing school, based on overall passing percentage.
 - This analysis cannot provide evidence that including the ninth grade scores for Thomas High School significantly affected the school's overall performance.
