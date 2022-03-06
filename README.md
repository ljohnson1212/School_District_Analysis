# School_District_Analysis

# Overview
	
	Maria and her supervisor have been notified that a file sent to them has shown evidence of academic dishonesty. The file is question is the students_complete.csv file. The file shows evidence of altered reading and math scores for Thomas High School ninth graders. The board does not know the full story of the academic dishonesty, so that they asked Maria to help. Our job is to assist Maria by updating the scores for Thomas High School ninth graders while keeping the remaining data the same. After completing the analysis, she would like a report to describe how the changes affect the overall analysis previously completed. 

#Results

	BEFORE DATA CLEANUP

		Average Math Score = 79.0
		Average Reading Score = 81.9
		% Passing Math 75
		% Passing Reading 86
		% Overall Passing 65

	AFTER DATA CLEANUP

		Average Math Score = 78.9
		Average Reading Score = 81.9
		% Passing Math 74.8
		% Passing Reading 85.7
		% Overall Passing 64.9

	Thomas High School Summary

	BEFORE DATA CLEANUP

		Thomas High School's % Overall Passing was 91.

	AFTER DATA CLEANUP

		Thomas High School's % Overall Passing was 65.

	OBSERVATION: Overall order change due to Thomas High School cleanup .

	Math and reading scores by grade - 
		Student count() Before THS Cleanup was: 1635 - 
		Student count() After THS Cleanup was: 1174
		Scores by school spending - Thomas HS is in the spending bucket "$601-650"

	Scores by school size
		Removing Thomas High School 9th Grade reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for the size.
		Removing Students from Thomas High School 9th Grade reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for spending bucket "$601-650"
		Thomas High School is allocated on Spending Bin "$601-650"

#Conclusion