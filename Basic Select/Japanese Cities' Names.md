### Question:

Query the names of all the Japanese cities in the CITY table. The COUNTRYCODE for Japan is JPN.
The CITY table is described as follows:

[Link to the problem](https://www.hackerrank.com/challenges/japanese-cities-name/problem?isFullScreen=true)


![City Table](images\1449729804-f21d187d0f-CITY.jpg)

### Solution:

```
select name from city where city.countrycode = 'JPN';
```