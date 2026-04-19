## Exploratory-data-Analysis-Python
Explore and derive insights from a multi-table dataset to understand underlying patterns and relationships.

### 🔧 Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) using Python on a custom dataset consisting of multiple related tables. The workflow demonstrates data preprocessing, transformation, merging, and analysis using structured problem statements.

### 📌 Tasks Performed
- Created three separate dataframes from the given tables and exported them as .csv files for further use.
- Handled missing values in the Project dataset by replacing them with a running average using a loop-based approach.
- Split the Name column in the Employee dataset into First Name and Last Name, and removed the original column.
- Merged all three datasets into a single consolidated dataframe named Final.
- Added a Bonus column, allocating a 5% bonus based on project cost for employees who successfully completed projects.
- Adjusted employee designation levels:
Demoted employees involved in failed projects
Removed employees with designation levels above 4
- Prefixed employee names with "Mr." or "Mrs." based on gender and removed the gender column.
- Promoted employees (designation level +1) if their age is above 29 using conditional logic.
- Calculated total project cost per employee and created a new dataframe TotalProjCost containing:
Employee ID
First Name
Total Project Cost
- Filtered and displayed employee records where the city name contains the letter "o".

### 🚀 Key Skills
- Data Cleaning & Preprocessing
- Handling Missing Values
- Data Transformation
- Data Merging & Aggregation
- Conditional Logic in Python

### 🛠️ Tech Stack
- Python
- Pandas
- NumPy
