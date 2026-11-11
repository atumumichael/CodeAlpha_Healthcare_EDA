# Healthcare Patient Data Analysis Using Python

## Project Overview
This project explores a healthcare dataset using Python to identify patterns in patient demographics, medical conditions, hospital admissions, billing amounts, and treatment-related records.

The project was completed as part of the CodeAlpha Data Analytics Internship.

## Objectives
- Clean and prepare healthcare data.
- Explore patient demographics and medical conditions.
- Analyse hospital admission patterns.
- Examine billing amounts and hospital stay duration.
- Create visualisations to communicate findings.

## Tools and Technologies
- Python
- Google Colab
- Pandas
- Matplotlib
- Jupyter Notebook

## Dataset
**Source:** [Healthcare Dataset – Kaggle](https://www.kaggle.com/datasets/prasad22/healthcare-dataset)

The dataset contains 55,500 records originally and 15 columns, including:
- Age and gender
- Medical condition
- Blood type
- Admission and discharge dates
- Hospital and insurance provider
- Billing amount
- Medication and test results

After removing 534 duplicate records, 54,966 records remained for analysis.

## Data Cleaning
- Checked for missing values; none were found.
- Identified and removed 534 duplicate records.
- Identified 106 negative billing records for further investigation.
- Converted admission and discharge dates into datetime format.
- Created age groups.
- Calculated hospital length of stay.

## Key Findings
- The cleaned dataset contains 54,966 records.
- The average patient age is approximately 51.54 years.
- The 66–89 age group has the highest number of records.
- Medical conditions have relatively balanced record counts.
- Elective admissions have the highest average billing amount.
- The average hospital stay is approximately 15.5 days.
- Test results are distributed relatively evenly across normal, abnormal, and inconclusive categories.

## Visualisations
The notebook includes charts showing:
1. Patient distribution by medical condition.
2. Patient distribution by age group.
3. Patient distribution by admission type.
4. Gender distribution.
5. Average billing by medical condition.
6. Average hospital stay by admission type.
7. Test results distribution.
8. Average billing by age group.

## Limitations
This is a publicly available educational dataset. Its records should not be treated as verified real-world hospital statistics or used to make clinical decisions. The reasons for negative billing amounts are also unknown.

## Conclusion
The project demonstrates how Python can be used to clean, explore, analyse, and visualise healthcare-related data. It provided practical experience with Pandas, Matplotlib, exploratory data analysis, and communicating findings through visualisations.

**Project Type:** Data Analytics Internship  
**Organisation:** CodeAlpha
