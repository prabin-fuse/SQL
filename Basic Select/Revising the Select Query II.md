### Question:

Query the NAME field for all American cities in the CITY table with populations larger than 120,000. The CountryCode for America is USA.

The CITY table is described as follows:

[Link to the problem](https://www.hackerrank.com/challenges/revising-the-select-query-2/problem?isFullScreen=true)

![CITY Table](images/1449729804-f21d187d0f-CITY.jpg)

### Solution:

```sql
SELECT NAME FROM CITY
WHERE COUNTRYCODE = 'USA' AND POPULATION > 120000;
```