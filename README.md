# HR-Dashboard-MySQL-PowerBI

![image](https://user-images.githubusercontent.com/56026296/229609893-b7b1f261-5941-45af-8322-1ccb2535d36b.png)

## Data Used

**Data** - HR Data with over 22000 rows from the year 2000 to 2020.

**Data Cleaning & Analysis** - MySQL Workbench

**Data Visualization** - PowerBI

## Questions

1. What is the gender breakdown of employees in the company?
2. What is the race/ethnicity breakdown of employees in the company?
3. What is the age distribution of employees in the company?
4. How many employees work at headquarters versus remote locations?
5. What is the average length of employment for employees who have been terminated?
6. How does the gender distribution vary across departments and job titles?
7. What is the distribution of job titles across the company?
8. Which department has the highest turnover rate?
9. What is the distribution of employees across locations by state?
10. How has the company's employee count changed over time based on hire and term dates?
11. What is the tenure distribution for each department?

## Summary of Findings
 - The workforce has a higher proportion of male employees.
 - The majority of employees are White, with Native Hawaiian and American Indian being the  least represented.
 - Employee ages range from 20 to 57 years old.
 - Employees are categorized into five age groups (18-24, 25-34, 35-44, 45-54, 55-64). The largest age group is 25-34, followed by 35-44, while the smallest is 55-64.
 - Most employees work at the headquarters, with fewer working remotely.
 - The average tenure for terminated employees is approximately 7 years.
 - Gender distribution across departments is fairly balanced, but there are generally more male employees.
 - The Marketing department has the highest turnover rate, followed by Training, while Research and Development, Support, and Legal departments have the lowest turnover rates.
 - A significant number of employees are from Ohio.
 - The net change in employee numbers has increased over the years.
 - The average tenure across departments is about 8 years, with Legal and Auditing having the longest tenure, while Services, Sales, and Marketing have the shortest.

## Limitations

 - Some records showed negative ages, so these were excluded from the analysis (967 records). Only ages 18 and above were considered.
 - Certain termination dates were set far into the future, so they were not included in the analysis (1,599 records). Only termination dates up to the current date were used.