# American Cities

## Problem

Query all columns for all American cities in the `CITY` table with populations greater than `100000`.

The `CountryCode` for America is `USA`.

## SQL Query

```sql
SELECT *
FROM CITY
WHERE CountryCode = 'USA'
  AND Population > 100000;
```

## Topics Covered

* SELECT
* WHERE
* AND
* Comparison operator `>`
* Filtering data
