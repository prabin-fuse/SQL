### Question:

Query the sum of the populations for all Japanese cities in CITY. The COUNTRYCODE for Japan is JPN.

#### Input Format

The CITY table is described as follows:

![alt text](images/1449729804-f21d187d0f-CITY-1.jpg)

[Question Link](https://www.hackerrank.com/challenges/japan-population/problem?isFullScreen=true)

### Solution: 
```
select sum(population) from city where countrycode = 'JPN';
```