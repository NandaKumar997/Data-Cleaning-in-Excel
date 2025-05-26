# Data-Cleaning-in Customer Personality Analysis dataset using Excel
I have worked on the dataset to perform the Data Cleaning using Excel
Identified the Missing values in the dataset and found 24 missing values in the Income column and replaced the empty cells with the Median of income.
When checked for the duplicates there were no duplicate rows found in the dataset.
Text Standardization was performed on marital_status to lowercase (e.g., Single → single) and Education capitalized properly (e.g., PhD → Phd).
Converted dt_customer to a consistent dd-mm-yyyy format.
Renamed all columns to Lowercase and Underscore-separated.
Converted income to numeric type and age column as int.
Added a new age column calculated as 2025 - year_birth.
