# Pandas-Challenge
Module_4 Solution
Include the following:

Total number of unique schools

Total students

Total budget

Average maths score

Average reading score

% passing maths (the percentage of students who passed maths)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed maths AND reading)

![Screenshot 2023-12-14 at 3 26 18 pm](https://github.com/Sunilkth/Pandas-Challenge/assets/151619918/e18659bb-bbbd-4efc-a629-5d9ccde56181)


Perform the necessary calculations and then create a DataFrame that summarises key metrics about each school.

Include the following:

School name

School type

Total students

Total school budget

Per student budget

Average maths score

Average reading score

% passing maths (the percentage of students who passed maths)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed maths AND reading)

![Screenshot 2023-12-14 at 3 27 55 pm](https://github.com/Sunilkth/Pandas-Challenge/assets/151619918/5927434b-4ec2-432b-b130-b34bc0ac0631)

Highest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in descending order and display the top 5 rows.

Save the results in a DataFrame called "top_schools".

Lowest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in ascending order and display the top 5 rows.

Save the results in a DataFrame called "bottom_schools".

Maths Scores by Year
Perform the necessary calculations to create a DataFrame that lists the average maths score for students of each year level (9, 10, 11, 12) at each school.

Reading Scores by Year
Create a DataFrame that lists the average reading score for students of each year level (9, 10, 11, 12) at each school.
![Screenshot 2023-12-14 at 3 29 21 pm](https://github.com/Sunilkth/Pandas-Challenge/assets/151619918/a8c1a1cb-62a8-4040-8cf7-f06678020962)
Scores by School Spending
Use the scores above to create a DataFrame called spending_summary.

Include the following metrics in the table:

Average maths score

Average reading score

% passing maths (the percentage of students who passed maths)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed maths AND reading)

Scores by School Size
Use the following code to bin the per_school_summary.

size_bins = [0, 1000, 2000, 5000]
labels = ["Small (<1000)", "Medium (1000-2000)", "Large (2000-5000)"]
Use pd.cut on the "Total Students" column of the per_school_summary DataFrame.

Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).

Scores by School Type
Use the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.

This new DataFrame should show school performance based on the "School Type".

![Screenshot 2023-12-14 at 3 30 30 pm](https://github.com/Sunilkth/Pandas-Challenge/assets/151619918/f62c9ea9-aea7-4ff0-bc20-b1e76db0c91f)
