# School District Analysis

### Overview of the school district analysis
Overview of the school district analysis
Maria, the Chief Data Scientist for a School District, is responsible for analyzing school data. Her analysis helps to make strategic decisions. This summary was done to present to the School Board. 

The report contains the following sections: 
  * District Summary
  * School Summary
  * Top & Bottom Five schools by the overall Passing percentage
  * Math and Reading Scores by Grade
  * Scores by School Spending per capita 
  * Scores by School Population Size
  * Scores by School Type
 
_Note:_ Due to an issue with the reading and math grades for Thomas High School (THS) ninth graders were replaced with NaN. This analysis was done by a second time impacting some scores. 


### Results
As the issue impacts the summary, it is considered to resolve the following questions to avoid any misunderstanding.
The student total is 39,170, THS 9th students are 461. When the grades were substracted from the total the math and reading scores were affected. 

  - _**How is the district summary affected?**_ 
  As you can see in the following images, the Passing Math and Reading Average and Percentage were affected, also the Overall Averge/Percentage due to subtracting from the total population, the THS 9th-grade.
 
_Previous result_
![PrevDistrictSummary](https://github.com/JackieCortes/School_District_Analysis/blob/main/Images_4/AnteriorDistrictS.png)
_Result after changes_
![District_Summary](https://github.com/JackieCortes/School_District_Analysis/blob/main/Images_4/District_Summary.PNG)
 
 
  - _**How is the school summary affected?**_
     The below images again show the impact in the THS metrics after removing the THS 9th-grade. It is essential to point out that School Type, Total Students, Total School Budget, Per Student Budget are metrics without impact, given the issue was in the scores. 
 
_Previous result_
  ![Previous_School_Summary](https://github.com/JackieCortes/School_District_Analysis/blob/main/Images_4/THS_Prev.png)
_Result after changes_  
  ![Remanufactured_School_Summary](https://github.com/JackieCortes/School_District_Analysis/blob/main/Images_4/THS_New.png)
  
  
  - _**How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**_
     The population will show a "na" value until further communication due to the current issue. So until this moment, there is no possibility of comparing grades with other schools.
  _Current Math Scores_   
  ![Math Scores_Summary](https://github.com/JackieCortes/School_District_Analysis/blob/main/Images_4/Math_by_Grade.PNG)
   _Current Reading Scores_  
  ![Reading_Scores_Summary](https://github.com/JackieCortes/School_District_Analysis/blob/main/Images_4/Read_by_Grade.PNG)
  
  
  - _**How does replacing the ninth-grade scores affect the following:**_
       -Math and reading scores by grade
       
       
       - Scores by school spending
       ![Scores_By_School_Spending](https://github.com/JackieCortes/School_District_Analysis/blob/main/Images_4/Scores_by_School_Spending.PNG)
  
       
       - Scores by school size
       
       ![Scores_By_School_Size](https://github.com/JackieCortes/School_District_Analysis/blob/main/Images_4/Scores_by_School_Size.PNG)
  
       - Scores by school type

       ![Scores_By_School_Type](https://github.com/JackieCortes/School_District_Analysis/blob/main/Images_4/Scores_by_School_Type.PNG)

### Summary: 
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
