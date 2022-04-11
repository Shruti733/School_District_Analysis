# School_District_Analysis (Pandas project)

## Overview of the project 

In this project, we were working on a `School district` data-set using jupyter notebook and pandas. Pandas is a python
library for data manipulation and analysis. Pandas is being used in this project along with the jupyter notebook to
read raw data in a csv file, clean and inspect the data, merge data-sets, perform calculations and create tables.

### Purpose 

The main purpose of the project was to re-analyze the school district data-set after certain discrepancies were found in the 9th grade students' data-set for Thomas High School. The analysis was required to be done regarding the school funding and standardized student test scores in order to make informed decisions related to school budgeting and prioritization.

## Results

- **Effect on district summary:**
  
  By looking at the below image, we can see that the average math and reading scores have slightly decreased.
  This has resulted in all the percentage numbers to decrease:

  ![district_summary](Image_analysis/district_summary.png)

- **Effect on school summary:**

  By looking at the below image, we can see that average math and reading scores of **Thomas High School** have decreased
  whereas, the average scores for all other schools did not change. This has resulted in all the percentage numbers to decrease:

  ![school_summary](Image_analysis/school_summary.png)

 - **Effect on Thomas High School’s performance relative to the other schools after replacing the ninth graders’ math and**
   **reading scores:**

  By looking at the below image, we can see that the Thomas High School's overall passing percentage has slightly decreased after replacing the ninth graders' math and reading scores but it has not affected the Thomas High Schools' ranking in comparison with other schools:

  ![rank](Image_analysis/rank.png)

  By looking at the below image, we can see that the math and reading scores for 9th graders of Thomas High School have changed
  to `NaN` whereas, the scores have not changed for any other school or grade as compared to older summary:

  ![math_grade_summary](Image_analysis/math_grade_summary.png)

  By looking at the below image, we can see that there are changes observed only in the **$631-645** bin row in the summary.
  The changes are outlined below:
  - Average Math Scores and correspondingly `% Passing Math` have slightly decreased.
  - Average Reading Scores have slightly increased whereas `% Passing Reading` has slightly decreased.
  - `% Overall Passing` has also slightly decreased.

  ![spending_summary](Image_analysis/spending_summary.png)

  By looking at the below image, we can see that there are changes observed only in the **Medium** school size category row in
  the summary. The changes are outlined below:
  - Average Math Scores and correspondingly `% Passing Math` have slightly decreased.
  - Average Reading Scores have slightly increased whereas `% Passing Reading` has slightly decreased.
  - `% Overall Passing` has also slightly decreased.

  ![size_summary](Image_analysis/size_summary.png)

  By looking at the below image, we can see that there are changes observed only in the **Charter** category school type row in
  the summary. The changes are outlined below:
  - Average Math Scores and correspondingly `% Passing Math` have slightly decreased.
  - Average Reading Scores have slightly increased whereas `% Passing Reading` has slightly decreased.
  - `% Overall Passing` has also slightly decreased.

  ![type_summary](Image_analysis/type_summary.png)

## Summary

The average math scores have decreased in the updated school/district summary after the "suspected" faulty 9th
grade math scores were replaced with NaN in the school district data-set. This indicates that the "faulty"
scores were falsely bloating the overall average to a higher number. Although the difference is quite small,
but it was still projecting a better performance by the students of Thomas High School. Due to this,
all buckets in which Thomas High School was categorized into were showing a slight better performance
which would have influenced the board decision of diverting additional funds for the school.

The average reading scores have increased in the updated school summary after the "suspected" faulty
9th grade reading scores were replaced with NaN in the school district data-set. However, the number
of passing students in reading have still decreased after the updates were made in the analysis.
This indicates that the "faulty" scores were falsely diminishing the overall average to a lower
number but projecting a better passing rate. Again, the difference is quite small, but it was still
projecting a better performance by the students in terms of passing rate in reading for Thomas High School.
Due to this, all buckets in which Thomas High School was categorized into were showing a slight better performance
in terms of passing rate in reading which would have influenced the board decision of diverting additional funds
for the school.
