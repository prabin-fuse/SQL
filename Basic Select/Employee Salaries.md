### Question:

Write a query that prints a list of employee names (i.e.: the name attribute) for employees in Employee having a salary greater than  per month who have been employees for less than  months. Sort your result by ascending employee_id.

#### Input Format

The Employee table containing employee data for a company is described as follows:

![alt text](images/1458557872-4396838885-ScreenShot2016-03-21at4.27.13PM.png)

where employee_id is an employee's ID number, name is their name, months is the total number of months they've been working for the company, and salary is their monthly salary.

#### Sample Input
![alt text](images/1458558202-9a8721e44b-ScreenShot2016-03-21at4.32.59PM.png)

#### Sample Output

```
Angela
Michael
Todd
Joe
```


#### Explanation

Angela has been an employee for  month and earns  per month.

Michael has been an employee for  months and earns  per month.

Todd has been an employee for  months and earns  per month.

Joe has been an employee for  months and earns  per month.

We order our output by ascending employee_id.


### Solution:
```
select name from Employee where salary > 2000 and months < 10 order by employee_id ASC;
```
