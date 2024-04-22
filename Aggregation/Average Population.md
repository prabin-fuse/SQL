### Question:
Query the average population for all cities in CITY, rounded down to the nearest integer.

#### Input Format

The CITY table is described as follows:

![alt text](images/1449729804-f21d187d0f-CITY.jpg)

[Question link](https://www.hackerrank.com/challenges/average-population/problem?isFullScreen=true)

### Solution:
```
select round(avg(population)) from city; 
```