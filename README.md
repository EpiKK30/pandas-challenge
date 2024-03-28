## PyCity Schools Analysis - Readme (pandas-challenge - Module 4 Challenge)

## Overview:
The PyCity Schools Analysis project involves the analysis of school performance using Pandas DataFrames. This analysis aims to assist in strategic decision-making regarding future school budgets and priorities for the city's school district. The project involves aggregating data on standardized test results, school information, and student demographics to identify trends in school performance.

## Files Included:
- **PyCitySchools.ipynb**: This Jupyter Notebook contains the Python scripts for the analysis. It includes code for loading, cleaning, and analyzing the school and student data using Pandas DataFrames.
- **Resources/schools_complete.csv**: CSV file containing data on school information, including school name, type, size, and budget.
- **Resources/students_complete.csv**: CSV file containing data on student information, including student ID, name, gender, grade, school name, reading score, and math score.

## Project Tasks:
The project involves performing the following tasks:

1. **District Summary**: Calculate key metrics for the entire school district, such as total number of schools, total number of students, total budget, average math and reading scores, and percentage of students passing math, reading, and both subjects.

2. **School Summary**: Generate a summary of key metrics for each school, including school name, type, total students, total school budget, per student budget, average math and reading scores, and percentage of students passing math, reading, and both subjects.

3. **Top Performing Schools**: Identify the top five performing schools based on overall passing percentage.

4. **Bottom Performing Schools**: Identify the bottom five performing schools based on overall passing percentage.

5. **Math and Reading Scores by Grade**: Calculate the average math and reading scores for students in each grade level (9th, 10th, 11th, and 12th) at each school.

6. **Scores by School Spending**: Categorize schools into spending ranges per student and analyze average math and reading scores, as well as passing percentages, for each spending range.

7. **Scores by School Size**: Categorize schools into size ranges based on total number of students and analyze average math and reading scores, as well as passing percentages, for each size range.

8. **Scores by School Type**: Analyze average math and reading scores, as well as passing percentages, for each school type (charter vs. district).

## Running the Analysis:
To run the analysis, follow these steps:

1. Ensure you have Python installed on your system.
2. Install Jupyter Notebook if you haven't already.
3. Clone this repository to your local machine.
4. Navigate to the project directory.
5. Open the Jupyter Notebook `PyCitySchools.ipynb`.
6. Run each cell in the notebook to execute the analysis scripts.

## Additional Notes:
- Make sure to replace the file paths in the notebook with the correct paths to the CSV files if they are stored in a different location.
- Refer to the comments in the notebook for detailed explanations of each step in the analysis.
- Feel free to modify the analysis scripts or expand upon them to gain deeper insights into school performance metrics.

## Command to Run the Notebook:
```
jupyter notebook PyCitySchools.ipynb
```

By following these instructions, you can conduct a comprehensive analysis of school performance using Pandas DataFrames and gain valuable insights to inform strategic decisions regarding school budgets and priorities.
