# Day 4 - HackerRank SQL

## Problems Solved: 05

---
```
### 1. Higher Than 75 Marks
'''sql
SELECT Name
FROM STUDENTS
WHERE Marks > 75
ORDER BY 
RIGHT(NAME,3),
ID ASC;

### 2. Employee Names
'''sql
SELECT name
FROM Employee
ORDER BY name ASC;

### 3. Employee Salaries
'''sql
SELECT name 
from Employee
where salary > 2000
AND months <10
ORDER BY employee_id ASC;

### 4. Type of Triangle
'''sql
SELECT 
CASE
    WHEN A + B <= C OR A + C <= B OR B + C <= A THEN 'Not A Triangle'
    WHEN A = B AND B = C THEN 'Equilateral'
    WHEN A = B OR B = C OR A = C THEN 'Isosceles'
    ELSE 'Scalene'
END
FROM TRIANGLES;

### 5. Weather Observation Station 15
'''sql
SELECT ROUND(LONG_W,4)
FROM STATION
WHERE LAT_N < 137.2345
ORDER BY LAT_N DESC LIMIT 1;
