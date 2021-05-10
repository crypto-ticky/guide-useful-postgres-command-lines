# Useful PostgreSql Command Lines On Ubuntu

## Access Postgres
```commandline
su - postgres
psql
```

#### Check Database List
```commandline
\list
```
or 
```commandline
\l
```
#### Create a New Database
```commandline
CREATE DATABASE test_db;
```
#### Drop Database
```commandline
DROP DATABASE [IF EXISTS] test_db;
```