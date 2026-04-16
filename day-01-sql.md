# Day 1 - HackerRank SQL

## Problems Solved: 06

---
```
### 1. Revising the Select Query II
'''sql
SELECT NAME FROM CITY
WHERE CountryCode = 'USA'
AND POPULATION > 120000;


### 2. Select By ID
'''sql
SELECT * FROM CITY
WHERE ID = 1661;


### 3. Japanese Cities' Names
'''sql
SELECT NAME FROM CITY
WHERE COUNTRYCODE = 'JPN'



### 4. Japanese Cities' Attribute
'''sql
SELECT * FROM CITY
WHERE COUNTRYCODE = 'JPN';



### 5. Weather Observation Station 1
'''sql
SELECT CITY, STATE FROM STATION;



### 6. Weather Observation Station 3
'''sql
SELECT DISTINCT CITY FROM STATION
WHERE ID % 2 = 0;


