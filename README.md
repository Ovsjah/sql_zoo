# sql_zoo
http://sqlzoo.net/wiki/SQL_Tutorial


## 1. Select basics

1)
```
SELECT population FROM world
  WHERE name = 'Germany'
```

2)
```
SELECT name, population FROM world
  WHERE name IN ('Sweden', 'Norway', 'Denmark');
```
