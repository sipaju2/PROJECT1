# Project-1 US Education Data

This dataset is designed to bring together multiple facets of U.S. education data into one convenient CSV.

## Contents

states_all_extended.csv: An extended version of states_all.csv; contains detailed enrollment data for race and gender.


### Identification
PRIMARY_KEY: A combination of the year and state name.
YEAR
STATE
Enrollment

A breakdown of students enrolled in schools by school year.

The following content describes each columns names in detail:
GRADES_PK: Number of students in Pre-Kindergarten education.
GRADES_4: Number of students in fourth grade.
GRADES_8: Number of students in eighth grade.
GRADES_12: Number of students in twelfth grade.
GRADES_1_8: Number of students in the first through eighth grades.
GRADES 9_12: Number of students in the ninth through twelfth grades.
GRADES_KG_12: Number of students in Kindergarten through twelfth grade.
GRADES_ALL: The count of all students in the state. Comparable to ENROLL in the financial data (which is the U.S. Census Bureau's estimate for students in the state).

The extended version of states_all contains additional columns that breakdown enrollment by race and gender. For example:
Grades_ALL_AS: Number of students whose ethnicity was classified as "Asian".
Grades_ALL_ASM: Number of male students whose ethnicity was classified as "Asian".
Grades_ALL_ASF: Number of female students whose ethnicity was classified as "Asian".
The represented races include AM (American Indian or Alaska Native), AS (Asian), HI (Hispanic/Latino), BL (Black or African American), WH (White), HP (Hawaiian Native/Pacific Islander), and TR (Two or More Races). The represented genders include M (Male) and F (Female).

Financials Information:
A breakdown of states by revenue and expenditure.

ENROLL: The U.S. Census Bureau's count for students in the state. Should be comparable to GRADES_ALL (which is the NCES's estimate for students in the state).
TOTAL REVENUE: The total amount of revenue for the state.

FEDERAL_REVENUE
STATE_REVENUE
LOCAL_REVENUE
TOTAL_EXPENDITURE: The total expenditure for the state.

INSTRUCTION_EXPENDITURE
SUPPORT_SERVICES_EXPENDITURE
CAPITAL_OUTLAY_EXPENDITURE
OTHER_EXPENDITURE
Academic Achievement

A breakdown of student performance as assessed by the corresponding exams (math and reading, grades 4 and 8):
AVG_MATH_4_SCORE: The state's average score for fourth graders taking the NAEP math exam.
AVG_MATH_8_SCORE: The state's average score for eight graders taking the NAEP math exam.
AVG_READING_4_SCORE: The state's average score for fourth graders taking the NAEP reading exam.
AVG_READING_8_SCORE: The state's average score for eighth graders taking the NAEP reading exam.

### Process: 
* Clear up data
* Analyze the followings data from 2006 to 2015:
   * Revenue & Expenditure each year and each state
   * Students' enrollments each year
   * How many students' enrollment in each state
   * Which state contributed maximum to the enrollment count change in 2007-2009
   * Local Revenue and Enrollment Count relation
   * Top ten states of enrollments 
   * Top ten states of revenues and expenditures
   * Each state's total revenues and expenditures
   * California's total revenues
   * California's total expenditures
   * Students performances by years and states
   * Student Per difference Races
   * Analysis of the change Year to year
   * Student Per Gender
   * Comparison of the Enrollement from one Gender to the other in terms of enrollment
 * Make powerpoint slides for final presentation



