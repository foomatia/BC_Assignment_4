# BC_Assignment_4
##Pandas Challenge

This assignment required us to use the schools_complete.csv and students_complete.csv to analyse the following:

District Summary
Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.
Include the following:

- Total number of unique schools
- Total students
- Total budget
- Average math score
- Average reading score
- % passing math (the percentage of students who passed math)
- % passing reading (the percentage of students who passed reading)
- % overall passing (the percentage of students who passed math AND reading)

School Summary
Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school.
Include the following:

- School name
- School type
- Total students
- Total school budget
- Per student budget
- Average math score
- Average reading score
- % passing math (the percentage of students who passed math)
- % passing reading (the percentage of students who passed reading)
- % overall passing (the percentage of students who passed math AND reading)

Highest-Performing Schools (by % Overall Passing)
- Sort the schools by % Overall Passing in descending order and display the top 5 rows.
- Save the results in a DataFrame called "top_schools".

Lowest-Performing Schools (by % Overall Passing)
- Sort the schools by % Overall Passing in ascending order and display the top 5 rows.
- Save the results in a DataFrame called "bottom_schools".

Math Scores by Grade
- Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Reading Scores by Grade
- Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Scores by School Spending
- Create a table that breaks down school performance based on average spending ranges (per student).
- Use the code provided below to create four bins with reasonable cutoff values to group school spending.
- Use pd.cut to categorize spending based on the bins.
- Use the given code to then calculate mean scores per spending range.

Include the following metrics in the table:
Average math score
Average reading score
% passing math (the percentage of students who passed math)
% passing reading (the percentage of students who passed reading)
% overall passing (the percentage of students who passed math AND reading)

Scores by School Size
- Use the given code to bin the per_school_summary.
- Use pd.cut on the "Total Students" column of the per_school_summary DataFrame.
- Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).

Scores by School Type
- Use the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.
- This new DataFrame should show school performance based on the "School Type".

Along with references from the Jupyter Notebooks discussed in class, I asked AskBCS for help when one pre-given code ran an unexpected Numpy error. I also used Stock Overflow to help me remove the index for two lines of code in order to allign with the results indicated in the starter file.

