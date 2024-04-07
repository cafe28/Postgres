To begin our assignment, we first transfer our CSV files and establish the schema for each table. We chose to add DROP Columns as a safety measure to ensure that if the tables already exist in the database, they are dropped before creating new ones. It helps in avoiding conflicts or errors due to existing tables with the same names. Each table is structured with specific columns and constraints tailored to its purpose. Here's a breakdown: Departments: This table contains information regarding various departments within the organization. It utilizes "dept_no" as the primary key, ensuring each department possesses a distinct identifier and name.

Follow, the provided SQL code comprises a series of SELECT queries designed to retrieve specific information from the database regarding employees and their respective departments. The first query retrieves the employee number, last name, first name, sex, and salary of each employee, joined with the salaries table to ensure accurate salary information. Subsequent queries further refine the data selection, including filtering employees hired in 1986, listing managers for each department, displaying department details for each employee, isolating employees with specific names or working in specific departments, and counting the frequency of each employee's last name. These queries collectively facilitate data analysis and reporting, offering insights into employee demographics, hiring trends, departmental structures, and name distributions within the organization.






