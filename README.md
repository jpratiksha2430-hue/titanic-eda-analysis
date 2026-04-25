# Titanic Exploratory Data Analysis (EDA)

This project performs a Mini Exploratory Data Analysis (EDA) on the Titanic dataset using Python.

## Project Overview
The goal of this analysis is to explore the dataset, clean missing values, and uncover meaningful patterns affecting passenger survival.

## Data Cleaning
- Filled missing values in the Age column using mean
- Dropped the Cabin column due to excessive missing values
- Handled missing values in Embarked column

## Feature Engineering
- Created a new feature **FamilySize** using SibSp and Parch

##  Analysis Performed
- Survival rate by Age Group
- Survival rate by Embarkation Port
- Survival rate by Family Size

##  Visualizations
- Histogram of Age distribution
- Correlation Heatmap
- Bar plot of Survival by Family Size

##  Key Insights
- Passengers with higher fares had better survival chances
- Small to moderate family sizes had higher survival rates
- Passenger class showed an inverse relationship with survival
- Embarkation port influenced survival rates
- Most passengers were young adults

##  Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn

## Files Included
- titanic_task3.ipynb (Jupyter Notebook with full analysis)

## Conclusion
The analysis shows that survival on the Titanic was influenced by multiple factors such as passenger class, fare, family size, and age. Exploratory Data Analysis helped in identifying important patterns and relationships in the dataset.
