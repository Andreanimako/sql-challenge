# sql-challenge

This module challenge involved using SQL to perform data modeling, data engineering and data analysis.
Six tables were provided that provided information about employees of Pewlett Hackard from 1980 to 1990s.
The task was to import the information provided in the six tables into a SQL database and then do analyisis to answer the following questions:

1.List the employee number, last name, first name, sex, and salary of each employee.

2.List the first name, last name, and hire date for the employees who were hired in 1986.

3.List the manager of each department along with their department number, department name, employee number, last name, and first name.

4.List the department number for each employee along with that employee’s employee number, last name, first name, and department name.

5.List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

6.List each employee in the Sales department, including their employee number, last name, and first name.

7.List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

8.List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

I started by developing an Entity realationship diagram using QUICKDBD, a free online tool.
The png file of the ERD has been uploaded as Employees ERD
The schema was then exported from quickdbd into pgAdmin, modified and saved as the schema to create the six tables in SQL.
The information within the tables were imported from the data folder into pgAdmin.
Analysis of the data was then carried out using SQL queries and the queries stored in ans sql file named Employees Analysis.

All the files were then added, committed and pushed into this github repository.
