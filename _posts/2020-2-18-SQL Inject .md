<div>{%- include extensions/netease-cloud-music.html id='501650' -%}</div>
## SQL注入

mysql基础语法：

查：

```sql
SELECT column_name,column_name FROM table_name;
```

筛选：返回唯一值

```sql
SELECT DISTINCT column_name,column_name FROM table_name;
```

where过滤：

```sql
SELECT column_name,column_name
FROM table_name
WHERE column_name operator value;
```

ORDER BY:

```SQL
SELECT column_name,column_name
FROM table_name
ORDER BY column_name,column_name ASC|DESC;
```

你以为我是拿来排序的，实际上我是看你字段数的！

插：

```sql
INSERT INTO table_name (column1,column2,column3,...)
VALUES (value1,value2,value3,...);
```

改：

```sql
UPDATE table_name
SET column1=value1,column2=value2,...
WHERE some_column=some_value;
```

删：

```sql
DELETE FROM table_name
WHERE some_column=some_value;
```

limit：

```sql
SELECT * FROM Websites LIMIT 2;
```

group_concat()

拼接字符串

union select:

```sql
SELECT expression1, expression2, ... expression_n
FROM tables
[WHERE conditions]
UNION [ALL | DISTINCT]
SELECT expression1, expression2, ... expression_n
FROM tables
[WHERE conditions];
```

copy:

```sql
CREATE TABLE newadmin AS
(
    SELECT username, password FROM admin
)
```

