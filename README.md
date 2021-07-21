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
As you can see removing these specific scores average and percentage decreased. 

   _Previous result_
   
   ![Previous_School_Summary](https://github.com/JackieCortes/School_District_Analysis/blob/main/Images_4/THS_Prev.png)

   _Result after changes_  
   ![Remanufactured_School_Summary](https://github.com/JackieCortes/School_District_Analysis/blob/main/Images_4/THS_New.png)
  
  
 - _**How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**_
     
     The population will show a "nan" value until further communication due to the current issue. So until this moment, there is no possibility of comparing grades with other schools, and as a result, THS can not show its 9th performance.
     
    _Current Math Scores_   
    ![Math Scores_Summary](https://github.com/JackieCortes/School_District_Analysis/blob/main/Images_4/Math_by_Grade.PNG)
  
    _Current Reading Scores_  
    ![Reading_Scores_Summary](https://github.com/JackieCortes/School_District_Analysis/blob/main/Images_4/Read_by_Grade.PNG)
  
  
 - _**How does replacing the ninth-grade scores affect the following:**_
  
   - Math and reading scores by grade
   
   Witout knowing the scores of THS 9th-grade there is no possibility to know the performance of 9th grade among the schools in the district. And its ranking position is not reliable. However, as the other grades (10th-12th) have the correct information, the dashboards showing the information grouping the data by grade, school, and subject could be good to make decisions on this level. 
       
   - Scores by school spending
   
   As you observed the THS metrics (average and percentages) has moved by hundreths. Due to the presentation of this spending category in integers, there is no change between the previous result and this one.  
             
     ![ScoresBySchoolSpending](https://github.com/JackieCortes/School_District_Analysis/blob/main/Images_4/Scores_by_School_Spending.PNG)
  
       
   - Scores by school size
   
   No impact was shown, due to the presentation of the metrics.
          ![Scores_By_School_Size](https://github.com/JackieCortes/School_District_Analysis/blob/main/Images_4/Scores_by_School_Size.PNG)
  
   - Scores by school type
   
   No impact was shown, due to the presentation of the metrics and the categories number.
       ![Scores_By_School_Type](https://github.com/JackieCortes/School_District_Analysis/blob/main/Images_4/Scores_by_School_Type.PNG)

### Summary:
   After performing this new review replacing the 9th-grades THS scores with NaN, we can conclude the following impacts:
   
   - 1 Change in THS averages and percentages scores for math and reading by school.
   - 2 Change in THS averages and percentages scores for overall by school.
   - 3 Change in averages and percentage scores by district.
   - 4 In the matrix by grades, there is no score for 9th-grade.
    

