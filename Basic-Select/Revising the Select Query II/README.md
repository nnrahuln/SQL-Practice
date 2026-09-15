# HackerRank – Querying American Cities by Population

## Problem

Query the `NAME` field for all American cities in the `CITY` table where the population is greater than `120000`.

The `CountryCode` for America is `USA`.

## SQL Solution

```sql
SELECT NAME
FROM CITY
WHERE COUNTRYCODE = 'USA'
  AND POPULATION > 120000;
```

## Explanation

* `SELECT NAME` → Gets the city names.
* `FROM CITY` → Uses the `CITY` table.
* `COUNTRYCODE = 'USA'` → Selects only cities in America.
* `POPULATION > 120000` → Selects cities with a population greater than 120,000.

## Skills Practiced

* SQL `SELECT`
* `WHERE` clause
* `AND` operator
* Filtering data
* Comparison operators

## Platform

**HackerRank – SQL**
