### Question:
Given the CITY and COUNTRY tables, query the names of all the continents (COUNTRY.Continent) and their respective average city populations (CITY.Population) rounded down to the nearest integer.

Note: CITY.CountryCode and COUNTRY.Code are matching key columns.

#### Input Format

The CITY and COUNTRY tables are described as follows:

![alt text](images/1449729804-f21d187d0f-CITY.jpg)

![alt text](images/1449769013-e54ce90480-Country.jpg)

[Question Link](https://www.hackerrank.com/challenges/average-population-of-each-continent/problem?isFullScreen=true)

### Solution:
```
select Country.Continent, FLOOR(AVG(City.Population))
from Country, City 
where Country.Code = City.CountryCode 
group by Country.Continent ;
```