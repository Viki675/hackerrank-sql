# Day 2 - HackerRank SQL

## Problems Solved: 04

---
```
### 1. Select All
'''sql
SELECT * FROM CITY;

### 2. Weather Observation Station 4
'''sql
SELECT COUNT(CITY) - COUNT(DISTINCT CITY) FROM STATION;

### 3. Weather Observation Station 5
'''sql
SELECT CITY, LENGTH(CITY)
FROM STATION
ORDER BY LENGTH(CITY),
CITY LIMIT 1;

SELECT CITY, LENGTH(CITY)
FROM STATION
ORDER BY LENGTH(CITY) DESC,
CITY LIMIT 1; 

### 4. Weather Observation Station 6
'''sql
select DISTINCT CITY
FROM STATION
WHERE CITY LIKE 'a%'
    OR CITY LIKE 'e%'
    OR CITY LIKE 'i%'
    OR CITY LIKE 'o%'
    or CITY LIKE 'u%';
