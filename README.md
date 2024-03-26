# pandas-challenge
Background
You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.

Summary of Analysis

    District Analysis - 15 total schools were in this data set and there were 39,170 students. There was a total budget of $24M with an overall passing percentage (>70 in math and reading) of 65.17%. Avg Math score was 78.99 while the average Reading score was 81.88. % passing in Math was 85.81% while reading was at 85.81%

    School Analysis - 7 at District level while 8 are Charter. Total student size ranges between 427 and 4976 with district schools having more students than the Charter. 

    Conclusion - Looking at % of overall Passing the top 5 schools were Charter while the bottom 5 were at the District level. As the budget per student went up the passing rate went down. The passing rate decreased as well when the student size increased
    
District Summary

A high level analysis on the district's created on the following key metrics

Total Schools
Total Students
Total Budget
Average Math Score
Average Reading Score
% Passing Math (The percentage of students that passed math.)
% Passing Reading (The percentage of students that passed reading.)
% Overall Passing (The percentage of students that passed math and reading.)

School Summary
Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school.

Include the following:

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

Highest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in descending order and display the top 5 rows.

Save the results in a DataFrame called "top_schools".

Lowest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in ascending order and display the top 5 rows.

Save the results in a DataFrame called "bottom_schools".

Math Scores by Grade
Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Reading Scores by Grade
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student).

Use the scores above to create a DataFrame called spending_summary.

Include the following metrics in the table:

Average math score

Average reading score

% passing math (the percentage of students who passed math)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed math AND reading)

Scores by School Size
Use pd.cut on the "Total Students" column of the per_school_summary DataFrame.

Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).

Scores by School Type
Use the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.

This new DataFrame should show school performance based on the "School Type".
