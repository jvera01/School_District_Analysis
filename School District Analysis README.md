# School_District_Analysis
# Module 4 Pandas and Jupyter Notebook

# Overview of the school district analysis: Explain the purpose of this analysis.
    Maria is Chief Data Scientist for the City School System. She is responsible for analyzing data from different sources, places, and formats. The State Board of Education tasked her with preparing all standardized test data for analysis, reporting, and presentation to provide insights about performance trends and patterns. In this module, we helped Maria analyze student funding and student standardized test scores to help the State Board of Education. These insights are used to inform discussions and strategic decisions at the school and district level.

    Here is the list of deliverables for the analysis of the school district: 
     - A high-level snapshot of the district's key metrics, presented in a table format
     - An overview of the key metrics for each school, presented in a table format
     - Tables presenting each of the following metrics:
       - Top 5 and bottom 5 performing schools, based on the overall passing rate
       - The average math score received by students in each grade level at each school
       - The average reading score received by students in each grade level at each school
       - School performance based on the budget per student
       - School performance based on the school size 
       - School performance based on the type of school

    The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for   Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

# Results: Using bulleted lists and images of DataFrames as support, address the following questions. 

  # How is the district summary affected?
     The district summary was affected with the following results. 
     
     - Average Math Score from 79.0 to 78.9
     - Average Reading Score from 81.9 to 81.9
     - % Passing Math from 75 to 74.8
     - % Passing Reading from 86 to 85.7
     - % Overall Passing from 65 to 64.9
     - No Change in the Total Students 39170
     - No change in the in the Budget amount $24,649,428.00

  # How is the school summary affected?
     The school summary was affected with the following results.
    
     Charter Results: No change 
     - Average Math Score from 83.5 to 83.5
     - Average Reading Score from 83.9 to 83.9
     - % Passing Math from 94 to 94 to 94
     - % Passing Reading from 97 to 97
     - % Overall Passing from 90 to 90
     
     District Results: No change
     - Average Math Score from 77.0 to 77
     - Average Reading Score from 81.0 to 81.0
     - % Passing Math from 67 to 67
     - % Passing Reading from 81 to 81
     - % Overall Passing from 54 to 54

   # How does replacing the ninth graders’ math and reading scores affect Thomas High School’s  performance relative to the other schools?
      - It did not affect the performance. They were still in the Top 5 Schools. 
   # How does replacing the ninth-grade scores affect the following:

       Here are the results of how it was affected.
     - Math and reading scores by grade
        ![Getting Started](mathscoresbygrade.PNG)
        ![Getting Started](readingscoresbygrade.PNG)   
     - Scores by school spending		
        ![Getting Started](scoresbyschoolspending.PNG)                                     
     - Scores by school size
        ![Getting Started](scoresbyschoolsize.PNG)
     - Scores by school type
        ![Getting Started](scoresbyshooltype.PNG)

# Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
  
   The major Changes in the data after replacing the Thomas High School with NaNs were the following.

    - The average math score went from 78.95 to 78.93.
    - The average reading score went from 81.87 to 81.85
    - The total number of student were 38709 with scores.  
    - The passing count was 28939 students.




