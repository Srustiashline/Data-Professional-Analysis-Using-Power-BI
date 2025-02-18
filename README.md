# Data-Professional-Analysis-Using-Power-BI

## Table of Contents
- [Introduction](#introduction)
- [Dataset Description](#dataset-description)
- [Analysis Goals](#analysis-goals)
- [Instructions for Using Power BI](#instructions-for-using-power-bi)
  - [Load the Dataset](#load-the-dataset)
  - [Data Transformation](#data-transformation)
  - [Data Modeling](#data-modeling)
  - [Data Visualization](#data-visualization)
  - [Report Creation](#report-creation)
  - [Publishing and Sharing](#publishing-and-sharing)
-  [Dashboard Snapshot](#dashboard-snapshot)
- [Conclusion](#conclusion)
- [License](#license)

## Introduction
This project analyzes survey data collected from data professionals. The goal is to uncover insights about their experiences, job satisfaction, challenges, and demographics. Power BI is used to visualize and interpret the data, providing a comprehensive analysis.

## Dataset Description
The dataset contains responses from a survey conducted among data professionals. The key columns in the dataset include:
- **Unique ID**: An anonymized identifier for each respondent.
- **Email**: The email of the respondent (anonymized).
- **Date Taken**: The date the survey was taken.
- **Time Taken**: The time the survey was taken.
- **Q6 - Job Satisfaction**: Ratings on various aspects of job satisfaction (e.g., Management, Upward Mobility).
- **Q7 - Difficulty in Entering the Field**: Respondents' perceived difficulty in breaking into the data profession.
- **Q8 - Job Preferences**: Important factors when looking for a new job (e.g., Remote Work, Salary).
- **Q9 - Gender**: Respondent's gender.
- **Q10 - Age**: Respondent's age.
- **Q11 - Country**: Country of residence.
- **Q12 - Education**: Highest level of education.
- **Q13 - Ethnicity**: Respondent's ethnicity.

## Analysis Goals
The primary objectives of this analysis are:
1. To understand the overall job satisfaction levels among data professionals.
2. To identify common challenges faced when entering the data profession.
3. To determine the most valued job factors for data professionals.
4. To explore demographic distributions such as gender, age, education, and ethnicity.

## Instructions for Using Power BI
To replicate this analysis in Power BI, follow these steps:

1. **Load the Dataset**:
    - Open Power BI Desktop.
    - Click on 'Get Data' and select 'Excel'.
    - Load the 'Data Professional Survey' sheet.

2. **Data Transformation**:
    - Use the Power Query Editor to clean and prepare the data.
    - Remove any unnecessary columns.
    - Handle missing values appropriately.

3. **Data Modeling**:
    - Create relationships if you have multiple tables (not applicable in this single sheet case).
    - Create calculated columns and measures using DAX (Data Analysis Expressions) as needed.

4. **Data Visualization**:
    - Create various visualizations to represent the insights.
    - Examples: Bar charts for job satisfaction, pie charts for gender distribution, and line graphs for age distribution.
    - Use slicers to enable interactive filtering of data based on different dimensions (e.g., country, education).

5. **Report Creation**:
    - Compile your visualizations into a comprehensive report.
    - Use the formatting options to make the report visually appealing and easy to understand.

6. **Publishing and Sharing**:
    - Publish the report to Power BI Service.
    - Share the report with stakeholders by providing access or embedding it into a website or application.
  
## Dashboard Snapshot
[Data Professional Survey Breakdown]![Screenshot 2024-07-17 195959](https://github.com/user-attachments/assets/4f22c6bd-6042-47b9-923c-6fa72aff7f3f)

## Conclusion
This project demonstrates how to perform a data professional analysis using Power BI. By following the steps outlined in this README, you can replicate the analysis and gain valuable insights from the survey data.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
