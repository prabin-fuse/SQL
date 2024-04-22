### Question:

Query all columns for all American cities in the CITY table with populations larger than 100,000. The CountryCode for America is USA.

The CITY table is described as follows:

![CITY Table](image.png)

[Question link](https://www.hackerrank.com/challenges/revising-the-select-query/problem)

### Solution:

```sql
SELECT * FROM CITY
WHERE COUNTRYCODE = 'USA' AND POPULATION > 100000;
```
