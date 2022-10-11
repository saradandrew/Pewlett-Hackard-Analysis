# Pewlett-Hackard-Analysis

## Overview
The purpose of this analysis is to determine the number of retiring employees per job title and to identify which employees are eligible to participate in the mentorship program at Pewlett Hackard. PostgreSQL is used to identify this information (queries were run from Excel files containing staff demographic info provided by management)and the information was then extracted into CSV files.

## Results
Four major points drawn from the analysis:
- There are over 72,000 retirement-age employees currently at the company.
- Of the retirement-age employees, over 25,000 are senior engineers.
- Over 24,000 of the retirement-age employees are senior staff while over 3,000 are technique leaders.
- There are less than 2,000 employees that are eligible for the mentorship program.

## Summary
As the "silver tsunami" begins to make an impact, roughly 50,000 senior level staff will need to be replaced and over 20,000 other roles will need to replaced as well.

The mentorship_eligibity query revealed that there are only 1.5k employees that qualify for the mentorship program. Therefore, there are not nearly enough qualified, retirement-ready employees available to mentor the next generation of Pewlett Hackard employees.

Another query that may provide more insight to the upcoming "silver tsunami" may be one that analyzes which department the mentorship-eligible employees currently work in and in which departments they have experience. I would also recommend an additional query to identify how many years each mentorship-eligible employee has worked in each department to ensure the next generation of PH employees are properly trained and mentored.
