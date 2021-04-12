# School_District_Analysis

## Purpose of Analysis
The purpose of this analysis was to assist the school board in removing all 9th grade reading and math grades from Thomas High School, as they appear to have been altered. The school board does not want to remove all grades from all schools, so it has asked to only remove those grades and continue with the findings from the test results.

The goal is to determine fund allocation to the schools based on performance.

## Results of Analysis

* Results of Changes to District Summary:
  * Since Thomas High School is a Charter School, District Schools are not affected by removing this grade
* Results to School Summary:
  * Thomas High's summary scores are significantly affected by removing the 9th grade scores. The Overall Passing Percentage drops from 90.95% to 65.07%, as shown in the tables below
  * Including 9th Grade:![school_summary_all](https://user-images.githubusercontent.com/80076110/114345200-e94afb80-9b26-11eb-8dc3-89f1f179d6df.png)
  * Excluding 9th Grade: ![school_summary_ten_twelve](https://user-images.githubusercontent.com/80076110/114345236-f831ae00-9b26-11eb-83ef-8899ac58b3d0.png)
* Affects of Thomas High School's changes relative to other schools:
  * After removing the 9th grade scores, Thomas High school dropped completely out of the Top 5 performing schools

* Math and Reading Scores by Grade are not affected other than changing 9th grade at Thomas High to "NaN":
  * ![Scores_by_grade](https://user-images.githubusercontent.com/80076110/114347764-1a2d2f80-9b2b-11eb-85d2-13de12675517.png)

* Scores by school spending changed in the range Thlmas High falls into, the $630-$644 per student spending range. The Average Math and Acerage Reading scores dropped lsighlty, however the overall pasing dropped from 63% to 56%
  * Prior to Excluding 9th Grade: ![scores_by_spending_all](https://user-images.githubusercontent.com/80076110/114347838-3f21a280-9b2b-11eb-86c7-1c2e2438ab3f.png)

  * After Excluding 9th Grade: ![scores_by_spending_10-12](https://user-images.githubusercontent.com/80076110/114347936-68423300-9b2b-11eb-96f8-bbc036acc0c4.png)

* Again, very insignificant changes to the Math and Reading scores for both school size and type, but Overall percentage dropped for both in the Medium and Charter size and type schools, respectively:

http://localhost:8889/notebooks/School_District_Analysis/PyCitySchools_Challenge.ipynb


## Summary

In summary, the reading and math average scores overall dropped after removing the 9th grade results from Thomas High. Thomas High also was a Top 5 performing school, and dropped out of the top 5 after excluding the 9th grade results from the testing data. 

Another major change after excluding the results were the drop in overall passing percentage in the $630-$644 per student spending range, the second highest range in the analysis.

Finally, the average scores for both reading and math dropped in the Charter school type, whereas the District scores remained unchanged.

