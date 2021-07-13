# School_District_Analysis

## Overview of the School District Analysis

In the school district analysis project some student scores were potentially not valid and the project was to do a reanalysis of the data set without the potentially invalid data.  The data set consisted of student_data_df and school_data_df.  The suspect student scores were nulled out in student_data, and a new data set was formed, school_data_complete_df which was a merge of the data sets student_data_df and school_data_df.  The school_data_complete_df data frame was used to create the district_summary_df data frame.  In the analysis, the keys and values of this dataframe was re-used after re-calculating the values of this data frame which accounted for subtracting out the potentially invalid data.  This re-analysis was summarized in a dataframe named per_school_summary_df.  Both school_data_complete_df and per_school_summary_df were  used to generate various outputs which could be used in comparison analysis.  The result of the changes in the datasets are discussed below.

The analyses are in the PyCitySchools_Challenge jupyter notebook.  It is organized where the new analysis is at the top of the file and the original analysis is below.  There is a separator showing the end of the new analysis.  The results below are from these analysis.

## Results
Using bulleted lists and images of DataFrames as support, address the following questions

1. How is the district summary affected?

Original
<img width="936" alt="Original district summary dataframe" src="https://user-images.githubusercontent.com/85037467/125468344-21b11021-1177-4679-969f-16cff258bb0d.png">

New
<img width="954" alt="New district summary" src="https://user-images.githubusercontent.com/85037467/125468451-ec3f524f-0230-4aa0-a422-f7682ac56e6c.png">



How is the school summary affected?

Thomas High School (THS)
<img width="991" alt="Header for results" src="https://user-images.githubusercontent.com/85037467/125468688-fa44a6e9-e121-48db-bc11-b2a1a8aabc3a.png">

With 9th grade grades included
<img width="979" alt="First THS summary" src="https://user-images.githubusercontent.com/85037467/125468751-a037a24b-d1e1-475d-9d07-069363eba5b9.png">

With 9th grade grades removed
<img width="994" alt="New THS summary" src="https://user-images.githubusercontent.com/85037467/125468859-7f501fc4-98d4-49f8-8446-8c5c062623a2.png">




How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Reference:  new and original top performers

Top performers origina[https://github.com/linearcoffeecup/School_District_Analysis/blob/main/Challeng%204%20images/Original/Original%20top%20performers.png]



THS dropped from second overall to third overall


How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
There was no affect on the top 5 schools
Scores by school spending
No affect
Scores by school size
Different bins were used so no conclusion can be drawn.
Scores by school type

No affect

Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs. 
