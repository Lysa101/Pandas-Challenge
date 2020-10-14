# pandas-challenge
pandas project 

#District Summary

#Calculate the total number of schools
#Calculate the total number of students
#Calculate the total budget
#Calculate the average math score
#Calculate the average reading score
#Calculate the percentage of students with a passing math score (70 or greater)
#Percentage of students with a passing reading score (70 or greater)
#Calculate the percentage of students who passed math and reading (% Overall Passing)
#Create a dataframe to hold the above results

School Summary
#Calculate the total student count
#School budget and per student
#Average reading and math scores
#Students who passed math and passed reading == df is new df and (df[ is one the using for info 
per_passing_math = df[(df["math_score"] >= 70)]
per_passing_reading = df[(df["reading_score"] >= 70)]

# Students who passed both math and reading
per_passing_math_and_reading = df[(df["reading_score"] >= 70)
                                               & (df["math_score"] >= 70)]