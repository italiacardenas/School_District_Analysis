# School District Analysis

## Overview of the School District Analysis
This is a Py City school district analysis to provide inside about students' performance trends and patterns that will be used to inform discussions and strategic decisions at the school and district level. This analysis uses studentfunding and standardized math and reading test scores. The data was aggregated to showcase trends and school performance to assist the  schoolboard and superintendent. The data was treated witrh the utmost confidentialioty under the Family Educational Rights and Priivacy Act (FERPA) which protects the privacy of student education records. The law applies to all schools that receive funds under an applicable program of the US Department of Education. After generating the data, the school board realized academic dishonesty took place and math and reading scores for Thomas High School were revisisted to replace the math and reading scores with NaNs in order to uphold state-testing standards. For this reason two analysis were run rather one, resulting in varying results.

The process was automated with Python 3.7.6 and Anaconda 4.9.2 The automation was successful and may be used to by other school districts.

## School District Analysis Results 
- **District Summary** The district summary was slightly negatively affected in the follwing categories:
  1. Total students: (461)
  2. Average Math Score: (.1)
  3. % Passing Math: (.2%)
  4. % Passing Reading: (.3%)
  5. % Overall Passing: (.1%)
  ![districtsummary.png](https://github.com/italiacardenas/School_District_Analysis/blob/40db5a4eff0cfd1f65c56c461fcb41b8b160586c/Resources/districtsummary.png)
- **School Summary:** The school summary was not affected aside from the changes in Thomas High School.
- **Thomas High School (THS) performance relative to other schools (post adjustment):** Follwing the adjustment, the percentage of passing students went down slightly, but it rem,ained in the top 5 schools.
    ![thssummary](https://github.com/italiacardenas/School_District_Analysis/blob/40db5a4eff0cfd1f65c56c461fcb41b8b160586c/Resources/thssummary.png)
- **How replacing ninth grade scores affected the following:**
  1. **Math and reading scores by grade** were not affected aside from THS ninth grade scores reading NaN.
  ![mathscores](https://github.com/italiacardenas/School_District_Analysis/blob/40db5a4eff0cfd1f65c56c461fcb41b8b160586c/Resources/mathscores.png) 
  2. **Scores by school spending:** The adjusted caused the overall passing percentage to slightly decrease scores by school spending by roughly .08 for spending range $630-644.  
  3. **Scores by school size** did not experience significant changes.  
  4. **Scores by school type:** Charter schools experienced a .04 decrease due to the adjustment.  
  
## School District Analysis Summary
Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs. Four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs:
1. Total Students - Because the scores for ninth grade students were replaced with NaN the total students count went from 39,170 to 38,709. This adjustment caused a significant impact in the rest of the data analysis.
2. Charter School data - Thomas High School is a charter school, therefore data regarding the school type also experienced a change.
3. Thomas High School - Average Reading Score - removing the ninth grade reading scores caused an increase in the Average Reading Score by .05.
4. Thomas High School - Overall Passing Percentage - removing the ninth grade reading scores caused a significant decrease in the Overall Passing Percentage by (.32).
