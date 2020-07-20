# PY City Schools Analysis

## Overview of Project

### Purpose

 * The purpose of this analysis is to take school data for students, schools, testing scores and budgets and create various comparisons using the data. furthermore we wanted to see if by eliminating math and reading scores from a particular grade and school. how would that affect the the various analysis going forward.


## Results

 * How is the District Summary Affected
		-  for the District summary, it reduces the overall Math and Reading averages for the entire district. this is because we have NaN for an entire grade within one of the schools in the district

 * How is the School Summary affected 
	   	- This just affects the Thomas High School results in there average scores and overall passing score for that particular school, since every school is calculated seperately 

 * How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
 		- it brings down there % passing scores in Math and in Reading, and then there o% overall passing score relative to the other schools in the district 

 * How does replacing the ninth-grade scores affect the following:
		Math and reading scores by grade
			- The average scores drop by a few percentage points for the 9th grade in the entire district 

		Scores by school spending
			- Thomas High school is in the 2nd highest bucket in spending, but has not made top 5 in % overall passing scores in part because of the missing grade 9 math and reading scores. 
			- you can see below how it affects the overall passing grade for the 630-644 speding bracket
			- ![./Resources/image1.png]
				
		

		Scores by school size
			- the scores for medium school sizes dips to 2nd in overall % passing, when before they were the highest. please see image below 
			- dipping approx 6% 
			- ![./Resources/image2.png]
		
		Scores by school type
			- schools by type still lean toward charter schools doing better than district schools, but the percentage drops from 90 to 87 overall. 
			- the anlysis still holds true that % overall passing still favours charter schools over disctrict
			- ![./Resources/image3.png]


### Summary

	* The major changes happened in the placement of the Thomas High School overall % passing relative to the other schools, it brought them down to where they were previously. they also brought the overall performace of the district down as well, with missing scores the district loses out on a higher overall % passing. In turn we see that the 9th grade scores dip significantly as well since we no longer have scores for 1 of the 15 schools in the discrict for the entire 9th grade. the school speding bucket in turn gets affected, once showing that the 630-644 bucket per student yeilded the highest results, this was then affected by the non test scores for that bracket. 