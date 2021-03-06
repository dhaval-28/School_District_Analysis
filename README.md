# School_District_Analysis

## Purpose
The file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. The purpose of this analysis is to replace the math and reading scores for Thomas High School ninth grade with NaNs while keeping the rest of the data intact. 
The main file is available at : ![Click here](https://github.com/dhaval-28/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb)


## Results:

### How is the district summary affected?
Below is the District summary before replacing 9th grade score with NaNs at Thomas High School. 
![District Summary after replacing 9th grade and THS](https://github.com/dhaval-28/School_District_Analysis/blob/main/Images/District_Summary_BeforeReplacement.png)

---> Summary after replacing 9th grade with NaNs at Thomas High School.  The average score at district level went down a bit but it did not change a lot. 
![District Summary before replacing 9th grade and THS](https://github.com/dhaval-28/School_District_Analysis/blob/main/Images/District_Summary_AfterReplacement.png)

### How is the school summary affected?
Below is the School summary before replacing 9th grade score with NaNs at Thomas High School. 
![School Summary after replacing 9th grade and THS](https://github.com/dhaval-28/School_District_Analysis/blob/main/Images/School_Summary_BeforeReplacement.png)

---> Summary after replacing 9th grade with NaNs at Thomas High School.  The average score at Thomas High School went down becuase number of students at Thomas High School reamined same. 
![School Summary before replacing 9th grade and THS](https://github.com/dhaval-28/School_District_Analysis/blob/main/Images/School_Summary_AfterReplacement.png)

---> Summary after replacing 9th grade with NaNs at Thomas High School and not including 9th grade students in total count.  The average score at Thomas High School reamined same. 
![School Summary before replacing 9th grade and THS](https://github.com/dhaval-28/School_District_Analysis/blob/main/Images/School_Summary_AfterReplacement2.png)

### How does replacing the ninth graders??? math and reading scores affect Thomas High School???s performance relative to the other schools?
As you can see in the images above, Thomas High School's overall performance went down from 90% to 65%. This puts Thomas High School from one of the top performing school to one of the average performing schools. 

### How does replacing the ninth-grade scores affect the following: Math scores by grade
NaN's did not substantially effect the output of our Math scores by grade.

Math Score Before replacing with NaNs :

![Math scores by grade](https://github.com/dhaval-28/School_District_Analysis/blob/main/Images/MathScore-at%20gradelevel-Before.png)

Math Score After replacing with NaNs :

![Math scores by grade](https://github.com/dhaval-28/School_District_Analysis/blob/main/Images/MathScore-at%20gradelevel-after.png)

### How does replacing the ninth-grade scores affect the following:Reading scores by grade
NaN's did not substantially effect the output of our Reading scores by grade.

Reading Score Before replacing with NaNs :

![Reading scores by grade](https://github.com/dhaval-28/School_District_Analysis/blob/main/Images/ReadingScore-at%20gradelevel-before.png)

Reading Score After replacing with NaNs :

![Reading scores by grade](https://github.com/dhaval-28/School_District_Analysis/blob/main/Images/ReadingScore-at%20gradelevel-after.png)

### How does replacing the ninth-grade scores affect the following:Scores by school spending
NaN's did not substantially effect the output of our spending summary.

Before
 
![Scores by school spending](https://github.com/dhaval-28/School_District_Analysis/blob/main/Images/Spending-Before.png)

After

![Scores by school spending](https://github.com/dhaval-28/School_District_Analysis/blob/main/Images/Spending-After.png)

### How does replacing the ninth-grade scores affect the following:Scores by school size
NaN's did not substantially effect the output of our scores by school size.

Before

![Scores by school size](https://github.com/dhaval-28/School_District_Analysis/blob/main/Images/SchoolSize-Before.png)

After

![Scores by school size](https://github.com/dhaval-28/School_District_Analysis/blob/main/Images/SchoolSize-After.png)

### How does replacing the ninth-grade scores affect the following:Scores by school Type
NaN's did not substantially effect the output of our Reading scores by school Type.

 Before
 
![Scores by school size](https://github.com/dhaval-28/School_District_Analysis/blob/main/Images/SchoolType-Before.png)

After

![Scores by school size](https://github.com/dhaval-28/School_District_Analysis/blob/main/Images/SchoolType-After.png)


## Summary

- Overall score of Thomas High School went down if 9th grade students from Thomas High school are included in total count
- If 9th grade students from Thomas High School are excluded in total count then there is extremely marginal change between the original score and new score.
- Score values for 9th grade at Thomas High School are NaN's for Maths and Reading in dataframe. 
- Once we update our data frame with the correct data, Thomas High School remains as a top 2 school in terms of passing percentage.

