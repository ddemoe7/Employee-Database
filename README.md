# Employee Database
SQL Exercise - Employee Database: A Mystery in Two Parts
<i>(sql-challenge)</i>

## Background
As a new data engineer at Pewlett Hackard, you are tasked with a research project on employees of the corporation from the 1980s and 1990s. All that remain of the database of employees from that period are six CSV files.

Design the tables to hold data in the CSVs, import the CSVs into a SQL database, and answer questions about the data. In other words, perform the following:
1. Data Modeling
2. Data Engineering
3. Data Analysis

## Results

<b>Data Modeling</b>
* Inspect the CSVs and sketch out an ERD (entity relationship diagram) of the tables.

![Entity Relationship Diagram (ERD)](https://user-images.githubusercontent.com/22499952/118580926-c2539b00-b75e-11eb-80aa-6eefe7263464.png)

<b>Data Engineering</b>
* Use the information to create a table schema for each of the six CSV files.

<b>Data Analysis</b>
* Once you have a complete database, answer the following questions:

1. List the following details of each employee: employee number, last name, first name, sex, and salary.
2. List first name, last name, and hire date for employees who were hired in 1986.
3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.
4. List the department of each employee with the following information: employee number, last name, first name, and department name.
5. List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."
6. List all employees in the Sales department, including their employee number, last name, first name, and department name.
7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.
8. In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.
