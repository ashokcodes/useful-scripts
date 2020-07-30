# Exporting Data as CSV

```
SELECT *
FROM table 
WHERE field = 1
INTO OUTFILE './data.csv'
FIELDS TERMINATED BY ','
ENCLOSED BY '"'
LINES TERMINATED BY '\n';
```
