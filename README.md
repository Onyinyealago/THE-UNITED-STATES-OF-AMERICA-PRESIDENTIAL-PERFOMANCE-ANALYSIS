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
- Tertiary GER %: The Gross Enrollment Ratio for tertiary (post-secondary) education, which includes all students enrolled in higher education as a percentage of the official age group for this level. A high tertiary GER indicates broad access to higher education.
- Female Tertiary GER %: This column shows the Gross Enrollment Ratio for females in tertiary education, giving insights into female participation in higher education and potential gender gaps.
- Male Tertiary GER %: The Gross Enrollment Ratio for males in tertiary education indicates male access to higher education and potential gender disparities compared to females.

4. **Unemployment table (Source: Worldbank.org):**
- Labor force, total: The total number of employable individuals
- Life expectancy: The estimate of the average lifespan of the population
- Net migration: the difference between immigrants and emigrants in a particular year
- Population, total: The total population of both male and female in a year
- Population,Female: Total number of the female gender
- Population, Male: Total number of the male gender
- Population Density:
- Unemployment with advanced education, female:  Female individuals with higher education credentials who are unable to find employment or are not currently working.
- Unemployment with advanced education, Male: Percentage of male individuals with higher education credentials who are unable to find employment or are not currently working.
- Unemployment with Intermediate education: Percentage of Individuals with Education beyond secondary school but not necessarily leading to university degree. Students with practical skills and knowledge for workforce but who are not currently working.

5. **Health table (Source: Worldbank.org)**
- Year: The year each corresponding value was retrieved
- Life expectancy at birth, (total): The average number of years a newborn is expected to live if the prevailing mortality rate remains constant throughout their life.
- Life expectancy at birth,(Male): The average number of years a male newborn is expected to live if the prevailing mortality rate remains constant throughout their life.
- Life expectancy at birth, (Female): The average number of years a Female newborn is expected to live if the prevailing mortality rate remains constant throughout their life.
- Hospital beds (per 1,000 people): The availability of inpatient services including public, private general and specialized hospitals.
- Number of neonatal deaths: Number of death occurring on children population with first 28 days after birth.
- Mortality rate on infants( per 1,000 live births): Number of death occurring on children population
- Mortality rate on adults (per 1,000 population): The probability rate of dying between the ages of 15 and 60 years.
- Suicide mortality rate on adults (per 1,000 population): Number of death by suicide.

## Data Modeling/Connection:
This analysis centered on the USA Presidents table, serving as the core fact table, with all related tables joined through a one-to-one relationship via the ‘year’ column.

![](https://github.com/Onyinyealago/THE-UNITED-STATES-OF-AMERICA-PRESIDENTIAL-PERFOMANCE-ANALYSIS/blob/main/Data%20Modeling%20Process.png)

## Data Analysis:
The analysis was shared between group members, dealing with the income and expenditure, population and health segment, Education and Unemployment rate in the US public sector.

### KEY PERFORMANCE INDICATOR ANALYSIS:
- Total Foreign Investment amounts to $207.33bn
- The Average inflation rate is 2.69%
- Average Education Expenditure amounts to 16.10%
- Average number of Hospital beds is 3.38

**1. Income and Expenditure**

Average Inflation Rate by Presidents:

This visual shows the average inflation rate during the tenure of each president in each political party.

**Detailed Breakdown:**
The Democratic Party was responsible for both the highest (5.61%) and lowest (1.36%) inflation rate experienced in a tenure within the scope of this analysis.
Within last three tenures of leadership, the average inflation rate has been on a rise, from 1.3% (Barrack Obama), to 1.9% (Donald Trump) to 5.61% (Joe Biden) with Joe Biden having the overall highest average inflation rate.

![](https://github.com/Onyinyealago/THE-UNITED-STATES-OF-AMERICA-PRESIDENTIAL-PERFOMANCE-ANALYSIS/blob/main/Avg%20Inflation.png)

**2. Total Gross Net Income by Presidents**

This chart shows the total GNI of each president during their tenure.

**Detailed Breakdown:**
Barrack Obama had the highest total GNI of $138.8tn, followed by George W. Bush with $122.0tn. The least total GNI was by George H. W. Bush with $29.1tn.

![](https://github.com/Onyinyealago/THE-UNITED-STATES-OF-AMERICA-PRESIDENTIAL-PERFOMANCE-ANALYSIS/blob/main/Total%20Gross%20Net%20Income%20by%20Presidents.png)

**3. Foreign Direct Investment**

This chart shows the total net federal direct investment over the years. The blue bars represent positive values while the red bars represent negative values. The negative values appear in years where the total investment export were more than the total investment import.

**Detailed Breakdown:**
Top 5 years with the highest FDI are 2004, 2007, 2011, 2020 and 2014.
Bottom 5 years with the least FDI are 2018, 2015, 2019, 2000 and 2016.
George H. W. Bush is the president that had the most occurrence of negative FDI values.

![](https://github.com/Onyinyealago/THE-UNITED-STATES-OF-AMERICA-PRESIDENTIAL-PERFOMANCE-ANALYSIS/blob/main/Foreign%20Direct%20Investment.png)

**4. Unemployment Rate with Advanced Education by President**

This visual showcases the unemployment rates for individuals with advanced education, segmented by U.S. presidents. The results reveal that Presidential economic policies and global economic events likely influenced advanced education unemployment, with minor gender disparity in this specific metric. This emphasizes the importance of policies that adapt to economic changes to maintain employment levels for highly educated individuals

**5. Average Youth Unemployment Rate (15-24 years) by President**

This chart displays the average youth unemployment rate for each president's term, focusing on ages 15-24. The analysis reveals Youth unemployment rates fluctuate based on economic conditions, with higher rates observed during recession periods. Economic recovery efforts seem to positively impact youth employment, as seen in recent years









