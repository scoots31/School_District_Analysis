# School_District_Analysis

## Overview of the School District Analysis

The school board has requested us to analyze the entire district involving funding and student grades and provide any new insights and performance of the schools. During the analysis we were informed of suspect results from a particular group of students at one of the schools. Our process was to perform the analysis twice - once with the full data set then again isolating the suspect data and excluding it.

## Results

* How is the district summary affected?

  First Look at District prior to pulling Thomas High School ninth-grade data out.
  ![Screen Shot 2021-12-16 at 12 34 57 PM](https://user-images.githubusercontent.com/93485455/146681606-8a95182d-fb11-44f6-9458-2016a035bc0b.png)

  After removing Thomas School ninth-grade data.
  ![Screen Shot 2021-12-16 at 12 29 19 PM](https://user-images.githubusercontent.com/93485455/146681685-8eb08bcb-8ea6-4a29-8957-459c68cbe22e.png)

  The data change resulted in a less than a half of a percentage point change in overall grade percentages.



* How is the school summary affected?

  First Look at School Summary prior to altering Thomas High School ninth-grade data.

  ![Screen Shot 2021-12-19 at 10 10 41 AM](https://user-images.githubusercontent.com/93485455/146682885-d00b1ce6-1387-413f-a266-5b69fe91a07f.png)


  Replacing Thomas School ninth-grade data with NANs.

  ![Screen Shot 2021-12-19 at 10 13 53 AM](https://user-images.githubusercontent.com/93485455/146682897-10461e08-5a65-4aaf-a0fd-105981b35eb0.png)


  Then omitting the ninth-grade data all together.

  ![Screen Shot 2021-12-19 at 10 32 08 AM](https://user-images.githubusercontent.com/93485455/146682905-850ba295-491f-4158-8096-a6604a2f9a32.png)




* How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?

  First Look at Top Schools prior to altering Thomas High School ninth-grade data.
  
  ![Screen Shot 2021-12-19 at 10 43 03 AM](https://user-images.githubusercontent.com/93485455/146683168-00f64af5-9322-46de-a0eb-f715e4ac42f4.png)

  Then omitting the ninth-grade data all together for Top Schools.

  ![Screen Shot 2021-12-19 at 10 44 09 AM](https://user-images.githubusercontent.com/93485455/146683208-8ced1e56-99e9-4b63-b49b-f0579cda4222.png)



* How does replacing the ninth-grade scores affect the following:

  * Math and reading scores by grade
  
    Math Scores before removing Thomas High School ninth-grade data
    
    ![Math 2021-12-19 at 11 19 32 AM](https://user-images.githubusercontent.com/93485455/146684359-03898e74-98a1-4cb1-88a2-b61355650026.png)

    Math Scores after removing Thomas High School ninth-grade data
  
    ![Math 2021-12-19 at 11 14 57 AM](https://user-images.githubusercontent.com/93485455/146684402-3930bead-be11-4ca1-8937-fe80b49829eb.png)

    Reading Scores before removing Thomas High School ninth-grade data
  
    ![Reading 2021-12-19 at 11 18 51 AM](https://user-images.githubusercontent.com/93485455/146684371-c2167fec-8853-4f08-a2f6-d5213c7fb0c0.png)

    Reading Scores after removing Thomas High School ninth-grade data
    
    ![Reading 2021-12-19 at 11 14 00 AM](https://user-images.githubusercontent.com/93485455/146684481-3231fe71-c9fe-475d-885a-07854a02b36e.png)


  
  * Scores by school spending
  
    First Look at Scores by School Spending prior to altering Thomas High School ninth-grade data.
    ![Screen Shot 2021-12-19 at 11 30 37 AM](https://user-images.githubusercontent.com/93485455/146684699-252d3166-dd7b-43a2-b13d-12a7ab638e05.png)
  
    Then omitting the ninth-grade data all together for Scores by School Spending.
    ![Screen Shot 2021-12-19 at 11 33 26 AM](https://user-images.githubusercontent.com/93485455/146684787-5c01787c-674c-4248-b295-47a3840f945e.png)

  
  
  * Scores by school size
  
    First Look at Scores by School Size prior to altering Thomas High School ninth-grade data.
    ![Screen Shot 2021-12-19 at 11 28 34 AM](https://user-images.githubusercontent.com/93485455/146684653-99c0bda1-88d1-442a-ac83-6f6b919e5138.png)
    
    Then omitting the ninth-grade data all together for Scores by School Size.
    ![Screen Shot 2021-12-19 at 11 32 46 AM](https://user-images.githubusercontent.com/93485455/146684769-e159355b-44db-4a82-8acc-d702f0df698f.png)

  
  
  * Scores by school type

    First Look at Scores by School Type prior to altering Thomas High School ninth-grade data.
    ![Screen Shot 2021-12-19 at 11 29 39 AM](https://user-images.githubusercontent.com/93485455/146684677-8c09dcda-4436-4a69-9d27-6d4f39fd2d70.png)

    Then omitting the ninth-grade data all together for Scores by School Type.
    ![Screen Shot 2021-12-19 at 11 32 03 AM](https://user-images.githubusercontent.com/93485455/146684746-8cc6660f-1444-4239-9688-1c9fa48beca5.png)


## Summary

Determination of the extent of the potential academic dishonesty or identify specific individuals to exclude from the dataset is not part of this analysis. Our analysis provides two paths for the district when trying to view the data. Viewing the data with the entire ninth grade of students from Thomas High School with their scores omitted from the results or leaving the data but replacing them with NaN.

Excluding the Thomas High School ninth graders and omitting their scores from the dataset, Thomas High School regained its high average scores and retained its position as the number two school in the district from the original analysis. The in-depth analysis of the district on spend, size, and type does not change all that much from the original analysis and the omitted ninth grade data. 

Relacing the ninth graders' scores with NaN caused Thomas High School's overall passing percentages and average scores to drop significantly. Thomas High School lost its placement as a top five school within this District. The district has also had its average math and reading scores decrease, as well as the overall passing percentage for students. 


