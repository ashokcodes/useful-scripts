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

# Comparing Lista
```
select instr(agent_list, ',') from progressive_calls where instr(agent_list, ',5,') <> 0; 
```

# Setting Max Connections
```
SET GLOBAL max_connections = 5000;
SHOW VARIABLES LIKE "max_connections";
```

# Setting Innodb Buffer Pool Size
```
-- 70% - 80% of RAM
SET GLOBAL innodb_buffer_pool_size=11811160064; 
SELECT @@innodb_buffer_pool_size/1024/1024/1024
```
