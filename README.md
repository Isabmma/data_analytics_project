# Data Analysis project

Let's make a complete exercise of pandas to a data analysis project. 

### What do we have?

We have data from 2019 of a service company. 

- CadastroFuncionarios
- CadastroClientes
- BaseServiçosPrestados

### What we want to know/do?  

1. Total value of the Salary Sheet -> What was the total expense on employee salaries by the company? <br>
    Calculate the total salary for each employee, salary + benefits + taxes, then sum all salaries

2. What was the company's revenue?<br>
    Calculate the total revenue for each service and then add the revenue for all

3. What % of employees have already signed a contract?<br>
    In the service base we have the employee who closed each service. But not all the employees that the company has have already closed some service.
    . In the employee base we have a list of all employees
    . We want to calculate Qty_Employees_Closed_Service / Qty_Employees_Totals
    . To calculate the number of employees who closed a service, use the service base and count how many employees there are. But remember, each employee can only be counted once.
    If you apply the .unique() method on a variable which is just 1 column of a dataframe, it will delete all duplicate values from that column.
    Ex: unique_columnA = dataframe['columnA'].unique() gives you as a response a list with all items in columnA appearing only once. All repeated values of columnA are excluded from the unicos_columnA variable

4. Calculate the total number of contracts that each area of the company has already closed


5. Calculate the total number of employees by area


6. What is the average monthly ticket (average monthly revenue) of the contracts?<br>
    .mean() calculates the average -> exemple: media_colunaA = dataframe['colunaA'].mean()

Ps: Recalling the most common options for encoding:<br>
encoding='latin1', encoding='ISO-8859-1', encoding='utf-8' ou então encoding='cp1252'