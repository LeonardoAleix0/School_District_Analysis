# **PyCitySchool District Analysis**

## Overview of Project

This project’s objective is to prepare standardized analysis, reporting insights, trends and patterns to support strategic decisions at the school and district level. The metrics covered in this analysis are below:

* The average math score received by students in each grade level at each school
* The average reading score received by students in each grade level at each school
* Top 5 and bottom 5 performing schools, based on the overall passing rate
* School performance based on the budget per student
* School performance based on the school size 
* School performance based on the type of school

## Data Source Information
The data source was divided in two tables, the student dataset and the school dataset. The student dataset provided information regarding the students such as student name, school name, math and reading scores and grades. The school dataset was composed of school name, type (District or Charter), size (student number) and budget. The tables were joined by the student id to provide a complete analysis of this dataset.

## Software
Python 3.7.6, Pandas, Jupyter Notebook

## Data cleaning
The column student name presented a number of prefixes that were removed, a change was also made to the 9th grade students from Thamos High School that had their reading and math scores replaced by a non value character as per request due to improper information.

## Results 

The school project is composed of 15 schools in which 7 schools are classified as District with the remaining schools classified as Charter. The total number of students is 39170 students and the total budget is $24,649,428.00. 

### District summary

The district summary had a drop of 1.1% in the math and reading score average and passing percentage with the change requested regarding Thomas High school. The columns Total Students and Total Budget maintained its original values.  


**Before**


![image](https://user-images.githubusercontent.com/86136535/126882333-2dd6d0f7-e25b-4c58-abcb-0195fdae25d1.png)



**After**


![image](https://user-images.githubusercontent.com/86136535/126882174-3c1d5768-42df-4f1e-a8b8-b792078d9591.png)



### School summary 


Thomas High School had a significant drop on their percentage of math and reading score. This change was caused mostly by changing the grades of the 9th but not changing the total number of students of the school. 


![image](https://user-images.githubusercontent.com/86136535/126882352-b8f6463a-66d4-43f4-891a-671a5a9ed24e.png)



![image](https://user-images.githubusercontent.com/86136535/126882366-c1dcb7fe-129f-4811-b34a-d9ddb2f7c0bd.png)




### Average of Math and reading scores in each grade level at each school.


![Avg math read](https://user-images.githubusercontent.com/86136535/126881840-f61426f8-b079-4fd0-aa54-4363cb33769b.png)



### Top 5 high ranked schools.


Thomas high school had minimum changes on its percentage numbers. 


![image](https://user-images.githubusercontent.com/86136535/126882449-a937a665-2197-458e-b273-2be67a7ea086.png)




### Bottom 5 performing schools.


![image](https://user-images.githubusercontent.com/86136535/126882452-257bc647-1e51-4b50-92c1-4c8d65c31904.png)


### School performance based on the budget per student


The spending ranges per student had minimum changes on the range $630-644 due to the changes applied to the Thomas High School. 


![image](https://user-images.githubusercontent.com/86136535/126882479-e7819316-3998-4bd9-bd44-420b5f6bcf8d.png)



![image](https://user-images.githubusercontent.com/86136535/126882486-e0abb522-8b28-4157-a7fc-89a35dcf5c4f.png)



### School performance based on the school size 


There was no change for the school size data. 


![image](https://user-images.githubusercontent.com/86136535/126882496-3fb3233c-ab30-470b-875d-3b1fc5bb39cc.png)


### School performance based on the type of school


There was no change on the performance by the type of school as Thomas High school is a Charter type school.


![image](https://user-images.githubusercontent.com/86136535/126882504-8067d6ff-f013-4052-83d5-266897e4f792.png)


## Summary

*	Based on the dataset, Charter type schools have higher math and reading average score than District type schools.

* Charter type schools spending ranges are smaller than the District type schools. 

*	The highest overall passing percentage a Charter type schools is 91%, a District type schools highest overall passing percentage is 54%.

*	Mathematics is the subject that District school needs to improve on.

*	District schools have more students and a larger school budget.

*	The school with the lowest spend per student in the district type schools is Bailey High School ($655 per student). Bailey high school has 4976 students. The school with the    highest spend per student in the Charter type is Thomas High School ($638), which has 1635 students.

