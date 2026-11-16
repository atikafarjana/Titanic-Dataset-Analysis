# Exploratory Data Analysis of the Titanic Dataset

## Project Overview

This project presents an Exploratory Data Analysis (EDA) of the Titanic passenger dataset using Python. The analysis focuses on understanding dataset structure, assessing data quality, examining passenger characteristics, and identifying patterns in survival and fare distributions.

The dataset consists of 891 passenger records and 12 attributes.

## Objectives

- Explore the dataset structure and identify feature types.
- Examine missing values and duplicate records.
- Analyze passenger survival counts and percentages.
- Investigate categorical variables, including passenger class, sex, and embarkation location.
- Examine passenger fare distribution using statistical and visualization techniques.

## Dataset Description

| Attribute | Description |
|---|---|
| Total Records | 891 |
| Total Features | 12 |
| Numerical Features | 5 |
| Non-Numerical Features | 7 |

Key features include PassengerId, Survived, Pclass, Sex, Age, SibSp, Parch, Fare, Cabin, and Embarked.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed

### 1. Data Exploration
- Inspected the first 10 and randomly selected records.
- Examined dataset dimensions and structure.
- Generated statistical summaries.

### 2. Data Quality Assessment
- Identified missing values across columns.
- Checked duplicate records.
- Examined numerical and categorical features.

### 3. Passenger Survival Analysis
- Calculated survival counts and percentages.
- Visualized survival distribution using a count plot.

### 4. Categorical Feature Analysis
Analyzed:
- Passenger Class (Pclass)
- Gender (Sex)
- Embarkation Location (Embarked)

### 5. Fare Distribution Analysis
Used three visualization techniques:
- Histogram (50 bins)
- Kernel Density Estimation (KDE)
- Box Plot

## Key Findings

| Analysis | Result |
|---|---|
| Total Passengers | 891 |
| Survived | 342 (38.38%) |
| Did Not Survive | 549 (61.62%) |
| Missing Age Values | 177 |
| Missing Cabin Values | 687 |
| Missing Embarked Values | 2 |
| Duplicate Records | 0 |
| Largest Passenger Class | Third Class (55.11%) |
| Male Passengers | 64.76% |
| Most Common Embarkation | Southampton (72.28%) |

### Fare Distribution Insights

- Mean fare: 32.20
- Median fare: 14.45
- Maximum fare: 512.33
- The distribution is positively skewed (right-skewed).

## Limitations

- A substantial number of Cabin values are missing.
- Some Age and Embarked values are missing.
- The analysis focuses on descriptive statistics and visualization.
- The findings identify patterns but do not establish causal relationships.
- No predictive machine learning model was developed in this project.

## Future Work

- Handle missing values using appropriate techniques.
- Investigate survival patterns across passenger groups.
- Perform correlation and feature analysis.
- Develop machine learning models for passenger survival prediction.
- Evaluate predictive performance using appropriate metrics.

## Conclusion

This project demonstrates the application of exploratory data analysis techniques to understand passenger characteristics, assess data quality, identify survival patterns, and examine fare distributions.

The analysis highlights the importance of data exploration and visualization as essential steps before conducting further statistical modeling or machine learning.

---

**Project Type:** Data Analysis / Exploratory Data Analysis  
**Author:** Atika Farjana
