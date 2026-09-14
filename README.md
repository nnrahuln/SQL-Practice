# HackerRank SQL Solutions

This repository contains my HackerRank SQL problem solutions.

## Problem
Query the names of American cities with population greater than 120000.

## SQL Solution

```sql
SELECT NAME
FROM CITY
WHERE COUNTRYCODE = 'USA'
  AND POPULATION > 120000;