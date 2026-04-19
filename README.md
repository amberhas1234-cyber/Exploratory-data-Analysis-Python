# Exploratory-data-Analysis-Python
Explore and derive insights from a multi-table dataset to understand underlying patterns and relationships.

This project focuses on performing Exploratory Data Analysis (EDA) using Python on a custom dataset consisting of multiple related tables. The workflow demonstrates data preprocessing, transformation, merging, and analysis using structured problem statements.

🔧 Project Overview

The dataset is divided into three tables, which are converted into individual dataframes and stored as CSV files. All subsequent operations are performed using these saved files.

📌 Tasks Performed
Task 1: Created three separate dataframes from the given tables and exported them as .csv files for further use.
Task 2: Handled missing values in the Project dataset by replacing them with a running average using a loop-based approach.
Task 3: Split the Name column in the Employee dataset into First Name and Last Name, and removed the original column.
Task 4: Merged all three datasets into a single consolidated dataframe named Final.
Task 5: Added a Bonus column, allocating a 5% bonus based on project cost for employees who successfully completed projects.
Task 6: Adjusted employee designation levels:
Demoted employees involved in failed projects
Removed employees with designation levels above 4
Task 7: Prefixed employee names with "Mr." or "Mrs." based on gender and removed the gender column.
Task 8: Promoted employees (designation level +1) if their age is above 29 using conditional logic.
Task 9: Calculated total project cost per employee and created a new dataframe TotalProjCost containing:
Employee ID
First Name
Total Project Cost
Task 10: Filtered and displayed employee records where the city name contains the letter "o".

🚀 Key Skills Demonstrated
Data Cleaning & Preprocessing
Handling Missing Values
Data Transformation
Data Merging & Aggregation
Conditional Logic in Python
Working with Multiple Dataframes
File Handling using CSV

🛠️ Tech Stack
Python
Pandas
NumPy
