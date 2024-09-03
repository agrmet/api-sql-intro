Write SQL SELECT statements to return films matching the below criteria:

# Standard Criteria
## All films
### QUERY
```sql
SELECT * FROM films;
```
## All films ordered by rating descending
### QUERY
```sql
SELECT * From films ORDER BY score DESC;
```
## All films ordered by release year ascending
### QUERY
```sql
SELECT * From films ORDER BY score ASC;
```
## All films with a rating of 8 or higher
### QUERY
```sql
SELECT * From films WHERE score >= 8;
```
## All films with a rating of 7 or lower
### QUERY
```sql
SELECT * From films WHERE score <= 7;
```
## Films released in 1990
### QUERY
```sql
SELECT * From films WHERE release_year = 1990;
```
## Films released before 2000
### QUERY
```sql
SELECT * From films WHERE release_year < 2000;
```
## Films released after 1990
### QUERY
```sql
SELECT * From films WHERE release_year > 1990;
```
## Films released between 1990 and 1999
### QUERY
```sql
SELECT * From films WHERE release_year BETWEEN 1990 AND 1999;
```
## Films with the genre of "SciFi"
### QUERY
```sql
SELECT * From films WHERE genre LIKE 'SciFi';
```
## Films with the genre of "Western" or "SciFi"
### QUERY
```sql
SELECT * From films WHERE genre LIKE 'SciFi' or genre LIKE 'Western';
```
## Films with any genre apart from "SciFi"
### QUERY
```sql
SELECT * From films WHERE genre NOT LIKE 'SciFi';
```
## Films with the genre of "Western" released before 2000
### QUERY
```sql
SELECT * From films WHERE genre LIKE 'Western' and release_year < 2000;
```
## Films that have the word "Matrix" in their title
### QUERY
```sql
SELECT * From films WHERE title LIKE '%Matrix%';
```

For the last query, you will need to research the LIKE keyword in postgres.

# Extension 1

## Return the average film rating
### QUERY
```sql

```
## Return the total number of films
### QUERY
```sql

```
## Return the average film rating by genre
### QUERY
```sql

```