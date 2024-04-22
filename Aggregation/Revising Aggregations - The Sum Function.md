### Question:

Query the total population of all cities in CITY where District is California.

### Input Format

The CITY table is described as follows:

![alt text](images/1449729804-f21d187d0f-CITY.jpg)

[Question Link](https://www.hackerrank.com/challenges/revising-aggregations-sum/problem?isFullScreen=true)

### Solution:
```
select sum(population) from city where district = 'California';
```
