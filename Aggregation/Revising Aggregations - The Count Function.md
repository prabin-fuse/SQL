### Question:
Query a count of the number of cities in CITY having a Population larger than 100,000 .

#### Input Format

The CITY table is described as follows:

![alt text](images/1449729804-f21d187d0f-CITY.jpg)

[Question Link](https://www.hackerrank.com/challenges/revising-aggregations-the-count-function/problem?isFullScreen=true)

### Solution:

```
select count(name) from city where population > 100000;
```