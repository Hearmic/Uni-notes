**

# 4. Methodology (25 marks)

## Most relevant existing variables

- ### Job bank data
    

|   |   |
|---|---|
|Column name|Explanation|
|NOC_CNP|Occupation code to merge with other datasets|
|NOC_Title|Occupation title  to merge with other datasets|
|ER_Code_Code_RE|Economic region codе|
|ER_Name_Nom_RE|Economic region name|
|Low_Wage_Salaire_Minium|Minimum wage of the occupation in question|
|Median_Wage_Salaire_Median|Median wage of the occupation in question|
|High_Wage_Salaire_Maximal|Maximum wage of the occupation in question|
|Annual_Wage_Flag_Salaire_annue|Annual salary flag for specific jobs|

- ### Canadian unemployment data 
    

|   |   |
|---|---|
|Column name|Explanation|
|REF_DATE|Date|
|GEO|Province|
|Age group|Age group|
|Employment|Number of persons who worked for profit, or unpaid family work|
|Full-time employment|Number of persons who worked 30 hours a week or more|
|Labour force|Number of persons who worked in the time period|
|Part-time employmenе|Number of persons who worked less than 30 hours a week|
|Unemployment|Number of persons who were without work|
|Employment rate|Employment/Population|
|Unemployment rate|Unemployment/Population|

  

- ### Statistics Canada Job Vacancy and Wage Survey data
    

|   |   |
|---|---|
|Column name|Explanation|
|North American Industry Classification System (NAICS)|NAICS ID|
|DGUID|Industry ID|
|Statistics|Job Vacancies/Payroll|
|Employees/Job Vacancy Rate|Employees/Job Vacancy Rate|
|UOM|Metric measuring the statistic (number/percent)|
|VALUE|The value corresponding to the statistic.|
|STATUS|metric that measures the quality of the data|

- ### Use of advanced or emerging technologies, by industry and enterprise size data
    

|   |   |
|---|---|
|Column name|Explanation|
|REF_DATE|Date|
|GEO|Location|
|DGUID|Industry ID|
|North American Industry Classification System (NAICS)|NAICS ID|
|Enterprise size|How many people work in that enterprise|
|Advanced or emerging technologies|contains important keywords|
|VALUE|The value corresponding to the statistic.|

  

## New variables to create (5 marks)

- AI_RELATED (boolean): 1 if Job is AI related (ML, computer vision, etc.), 0 if it is not
    
- AI_ IMPACT (float): derived using the number of occupations related to the development of AI related to the previous year (-1 to 1) 
    

JB_year (integer): flag the year of Job Bank data.**