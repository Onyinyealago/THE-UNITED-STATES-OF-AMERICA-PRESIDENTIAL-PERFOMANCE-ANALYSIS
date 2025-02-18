# THE UNITED STATES OF AMERICA PRESIDENTIAL PERFOMANCE ANALYSIS (1990 – 2023)

## Introduction
TDI Governance Analyst comprises of Four individuals who provide analysis to potential client. Our mission is to provide detailed understanding into the public sector of a country. This report will provide analysis into various aspect of the country to evaluate the progress of the economy.

## Objectives
- Assess the performance of recent U.S. presidents (1990–2023) in key areas: Education, Employment, Health, and Federal Investment.
- Identify key metrics and trends, including life expectancy, education expenditure, inflation, and unemployment.
- Provide insights into government effectiveness and areas for improvement.

## Data Sourcing
We identified crucial factors in the US public sector to extract data and create a comprehensive analysis, combining metrics like unemployment rate, public services and population demographics to understand the economy’s overall health, identify trends, risks and areas of opportunity.

## Data Cleaning:
The subsequent procedures ensured the data’s accuracy and preparation for analysis:

1. **Checking for Missing Values:**
During the review of all tables, some values were missing in the early years records and recent years in some columns. These empty values were addressed by replacing them with the average of the proceeding / preceeding 10 values. There was no missing values in the USA Presidents table.

2. **Remove Duplicates:**
No duplicates were found in the tables.

3. **Verify Data Types**
All the columns were scanned to ensure proper data types. While most of the columns had the correct data type, columns that were set to be in percentage did not have the correct data type. This was corrected by dividing the values by 100 and setting the columns to be in percentage data type.

## Data Overview:
This analysis was done using five different tables and each table contains the following columns:
1. **U.S.A Presidents Table (Source: Github):**
- Year: The year each corresponding value was retrieved.
- Name: The name of president in office.
- Party: The political party of the president in office.
- Years In Office: The years the president was in office.
- Number: The nth position of the president.
 
2. **Income and Expenditure Table (Source: Worldbank):**
- Year: The year each corresponding value was retrieved.
- Gross Domestic Product (GDP): The total monetary value of all goods and services produced within a country's borders in a specific time period.
- Gross National Income (GNI): The total income earned by a country’s residents and businesses, including any income from abroad, over a specific time period.
- Inflation Rate: The percentage increase in the average price level of goods and services in an economy over a specific period, typically a year.
- Gross National Expenditure (GNE): The total spending by a country on goods and services within its borders, including both private and government spending.
- Foreign Direct Investment (FDI): Investment made by a foreign entity in the assets or ownership of a business in another country.

3. **Education Table (Source: WorldBank.org):**
- Primary GER % (Gross Enrollment Ratio): This column shows the Gross Enrollment Ratio for primary education, reflecting the total enrollment in primary education (regardless of age) as a percentage of the official primary school-age population. GER can exceed 100% due to early or late school entry.
- Female Primary GER %: This is the Gross Enrollment Ratio specifically for females in primary education, providing insights into female access to primary schooling and potential gender disparities in enrollment.
- Male Primary GER %: The Gross Enrollment Ratio specifically for males in primary education, indicating male access to primary schooling and potential disparities when compared to female GER.
- Secondary GER %: This column represents the Gross Enrollment Ratio for secondary education, showing the total enrollment in secondary education as a percentage of the official age group for that level. It indicates the reach of secondary education, including over-age and under-age students.
- Female Secondary GER %: The Gross Enrollment Ratio for females in secondary education, highlighting female access to secondary schooling and gender equity at this level.
- Male Secondary GER %: This is the Gross Enrollment Ratio for males in secondary education, showing male access to secondary schooling and any potential disparities relative to female enrollment.
- Tertiary GER %: The Gross Enrollment Ratio for tertiary (post-secondary) education, which includes all students enrolled in higher 






