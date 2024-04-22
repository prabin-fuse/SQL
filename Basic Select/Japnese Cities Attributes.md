### Question:

Query all attributes of every Japanese city in the CITY table. The COUNTRYCODE for Japan is JPN.

The CITY table is described as follows:

[Link to the problem](https://www.hackerrank.com/challenges/japanese-cities-attributes/problem)

![CITY Table](images\1449729804-f21d187d0f-CITY.jpg)

### Solution:

```sql
SELECT * FROM CITY WHERE COUNTRYCODE = 'JPN';
```