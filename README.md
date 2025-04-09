# Pandas-Challenge
In this project, I've created and manipulated Pandas DataFrames to analyze school and standardized test data. 

Performed the necessary calculations and then created a high-level snapshot of the district's key metrics in a DataFrame.

Included the following:

Total number of unique schools

Total students

Total budget

Average math score

Average reading score

% passing math (the percentage of students who passed math)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed math AND reading)

School Summary:
Performed the necessary calculations and then created a DataFrame that summarizes key metrics about each school.

Included the following:

School name

School type

Total students

Total school budget

Per student budget

Average math score

Average reading score

% passing math (the percentage of students who passed math)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed math AND reading)

Highest-Performing Schools (by % Overall Passing):
Sorted the schools by % Overall Passing in descending order and display the top 5 rows.

Saveed the results in a DataFrame called "top_schools".

Lowest-Performing Schools (by % Overall Passing):
Sorted the schools by % Overall Passing in ascending order and display the top 5 rows.

Saved the results in a DataFrame called "bottom_schools".

Math Scores by Grade:
Performed the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Reading Scores by Grade:
Created a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Scores by School Spending:
Created a table that breaks down school performance based on average spending ranges (per student).

Used the code provided below to create four bins with reasonable cutoff values to group school spending.

Used pd.cut to categorize spending based on the bins. Used the following code to then calculate mean scores per spending range.

Used the scores above to create a DataFrame called spending_summary.

Included the following metrics in the table:

Average math score

Average reading score

% passing math (the percentage of students who passed math)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed math AND reading)

Scores by School Size:
Used the following code to create three bins with reasonable cutoff values to group school size.

Created a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).

Scores by School Type:
Used the per_school_summary DataFrame to create a new DataFrame called type_summary.

This new DataFrame should show school performance based on the "School Type".
