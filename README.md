Project Title

Data Cleaning & Preprocessing on Titanic Dataset

Problem Statement

The objective of this project is to clean and preprocess the Titanic dataset before performing data analysis or machine learning. The raw dataset contains missing values, duplicate records, inconsistent data types, and non-standard column names. These issues need to be resolved to improve data quality.

Dataset Details
Dataset Name: Titanic Dataset
File Format: CSV
Number of Records: 891
Features Include:
Passenger ID
Passenger Class
Name
Gender
Age
Ticket
Fare
Cabin
Embarked
Survival Status
Approach

The following preprocessing steps were performed:

Loaded the Titanic dataset using Pandas.
Identified missing values.
Filled missing values in the Age column using the median.
Filled missing values in the Embarked column using the mode.
Removed the Cabin column because it contained a large number of missing values.
Removed duplicate records.
Converted important columns into appropriate data types.
Renamed column names for better readability.
Saved the cleaned dataset as Titanic_Cleaned.csv.
Results
Missing values handled successfully.
Duplicate rows removed.
Data types converted correctly.
Column names standardized.
Clean dataset generated and saved as Titanic_Cleaned.csv.
The dataset is now ready for Exploratory Data Analysis (EDA) and Machine Learning.
