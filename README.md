README: Overview of the ABC Company Data Analysis Project
Project Overview
This project analyzes employee data from ABC Company, focusing on various aspects such as team distribution, employee positions, age demographics, salary expenditure, and the correlation between age and salary. The dataset includes the following columns:

Name: Employee's name
Team: Department or team the employee belongs to
Number: Employee number
Position: Job title
Age: Employee's age
Height: Employee's height (with some incorrect entries)
Weight: Employee's weight
College: College attended (contains null values)
Salary: Employee's salary (contains null values)


Data Preprocessing Steps
Height Correction: The Height column contained incorrect data. All invalid entries were replaced with random values ranging from 150 to 180 cm.
Handling Null Values:
Salary: Rows with null salary values were filled with the median of the existing salary values to maintain data integrity for analysis.
College: Null values in the College column were replaced with the string 'Unknown' to ensure all entries are complete.


Analysis Tasks
Employee Distribution Across Teams: Calculated the number of employees per team and determined the percentage split relative to the total number of employees.
Segregation by Position: Analyzed the distribution of employees based on their positions within the company.
Predominant Age Group Identification: Identified the most represented age group among employees.
Salary Expenditure Analysis: Discovered which team and position have the highest salary expenditure.
Correlation Investigation: Explored the correlation between age and salary and represented this relationship visually.
Graphical Representations

1. Distribution of Employees Across Teams
A bar plot was created to illustrate the distribution of employees across the 30 teams:

Largest Teams:
New Orleans Pelicans (19 employees) and Memphis Grizzlies (18 employees) are the largest.
Average Team Size: Most teams have around 15 employees, indicating the company's standard team size.
Smaller Teams:
Orlando Magic and Minnesota Timberwolves each have 14 employees, which may indicate smaller departments or recent vacancies.

2. Distribution of Positions
A bar plot illustrated the distribution of employee positions:

SG (Shooting Guard): 102 employees
PF (Power Forward): 100 employees
PG (Point Guard): 92 employees
SF (Small Forward): 85 employees
C (Center): 79 employees (fewest, indicating a more specialized role).

3. Distribution of Age Groups
A horizontal bar plot displayed the distribution of age groups:

18-25: 200 employees (indicating a focus on hiring recent graduates).
26-30: 167 employees (solid presence of early-career professionals).
31-35: 68 employees
36-40: 20 employees (indicating fewer employees as age increases).
4. Salary Expenditure by Team and Position
Grouped by team and position to identify the highest salary expenditures, the top 15 were plotted:

Highest Salary:
Los Angeles Lakers lead with $31,866,445 for the SF position, reflecting significant investment.
Miami Heat ($31,538,671, PF) and Houston Rockets ($28,122,883, SG) follow closely.


5. Correlation Between Age and Salary
A scatter diagram illustrated the relationship between age and salary:

The correlation coefficient is 0.21, indicating a weak positive correlation. This suggests that while salary tends to increase slightly with age, other factors likely play a more significant role in determining salary levels within the organization.

Additional Information
This analysis provides insights into employee demographics, team structure, and financial commitments across the organization. The findings can inform future hiring strategies, salary negotiations, and departmental resource allocations.

This comprehensive overview serves as a foundation for further exploration and understanding of the company’s workforce dynamics.
