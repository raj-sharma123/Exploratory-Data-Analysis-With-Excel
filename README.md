# Exploratory Data Analysis With Excel of Titanic Dataset
![Titanic](https://github.com/user-attachments/assets/69e8fbb9-f716-4ed8-bd32-b93a72d8f786)


## Introduction

The **RMS Titanic** was a British passenger liner that tragically sank on **April 15, 1912**, during its maiden voyage from **Southampton**, England, to **New York City**, after colliding with an iceberg. The **Titanic dataset** is a widely recognized dataset in the data science community and is frequently used for exploratory data analysis and machine learning practice.

This dataset contains detailed information about the passengers aboard the Titanic, including personal attributes (such as age, gender, and name), travel details (such as ticket fare, class, and port of embarkation), and an important outcome label indicating whether or not each passenger **survived** the disaster.

In this project, we will conduct a thorough **Exploratory Data Analysis (EDA)** of the Titanic dataset using **Microsoft Excel**. The goal is to uncover meaningful patterns, trends, and insights related to passenger survival based on different features.

## Dataset Structure
The dataset consists of 12 columns:
1. **PassengerId:** Unique identifier for each passenger.
2. **Survived:** Survival status (0 = No, 1 = Yes).
3. **Pclass:** Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).
4. **Name:** Name of the passenger.
5. **Sex:** Gender of the passenger.
6. **Age:** Age of the passenger in years.
7. **SibSp:** Number of siblings/spouses aboard the Titanic.
8. **Parch:****** Number of parents/children aboard the Titanic.
9. **Ticket:** Ticket number.
10. **Fare:** Passenger fare (is in Pre-1970 British Pounds).
11. **Cabin:** Cabin number.
12. **Embarked:** Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton).

## Summary of Dataset
 * The dataset includes **891** rows, each representing a passenger.
 * The **"Survived"** column indicates whether a passenger survived the sinking of the Titanic.
 * The **"Pclass"** column indicates the class of the passenger, which is a proxy for socio-economic status (1st ~ Upper; 2nd ~ Middle; 3rd ~ Lower).
 * Missing values are present in the "Age", "Cabin", and "Embarked" columns.

# Analysis of the Dataset
## Descriptive Statistics
The dataset contains 891 records with the following summary statistics for the numerical columns:
1. PassengerId: Ranges from 1 to 891.
2. Survived: 38.38% of the passengers survived.
3. Pclass: Most passengers are in the 3rd class.
4. Age: The average age of passengers is approximately 29.7 years. The youngest passenger is 0.42 years old, and the oldest is 80 years old.
5. SibSp: On average, passengers have 0.52 siblings or spouses aboard.
6. Parch: On average, passengers have 0.38 parents or children aboard.
7. Fare: The average fare is 32.20, with a wide range from 0 to 512.33.

## Missing Values
 * Age: 177 missing values.
 * Cabin: 687 missing values.
 * Embarked: 2 missing values.

## Exploratory Data Analysis (EDA):
 * **Survival Rate Analysis:** Analyzing how survival rates differ based on features like class (Pclass), sex, age, and embarked port.
 * **Visualizations:** Create histograms, box plots, bar charts, scatter plots and treemap charts to explore relationships between features.

## Survival Rate by Class
 * 1st Class: 62.96%
 * 2nd Class: 47.28%
 * 3rd Class: 24.24%

Passengers in the 1st class had a significantly higher survival rate compared to those in the 2nd and 3rd classes.

## Survival Rate by Gender
 * Female: 74.20%
 * Male: 18.89%

Females had a much higher survival rate compared to males.

## Survival Rate by Embarkation Port
 * Cherbourg (C): 55.36%
 * Queenstown (Q): 38.96%
 * Southampton (S): 33.90%

Passengers who embarked from Cherbourg had the highest survival rate.

## Survival Rate by Age Group
 * 0-10 years: 61.29%
 * 10-20 years: 40.20%
 * 20-30 years: 35.00%
 * 30-40 years: 43.71%
 * 40-50 years: 38.20%
 * 50-60 years: 41.67%
 * 60-70 years: 31.58%
 * 70-80 years: 14.29%

Children (0-10 years) had the highest survival rate, followed by passengers aged 30-40 years.

## Conclusion
 * Sex is a major determinant of survival – females had a significantly higher survival rate than males, suggesting priority in rescue efforts.
 * Age played a role, with children having better survival rates.
 * Survivors generally paid higher fares. First-class passengers paid higher fares and had much better survival outcomes.
 * Port of Embarkation also influenced survival, with Cherbourg having the highest survival rate.
 * First-class passengers and those who boarded at Cherbourg had much higher survival rates.
 * Family size impacted survival, with very small families doing better.
