# sql-learn

```sql
mysql> SHOW databases;
+--------------------+
| Database           |
+--------------------+
| information_schema |
| mysql              |
| performance_schema |
| sys                |
+--------------------+
4 rows in set (0.00 sec)

```

```sql
mysql> CREATE DATABASE sekolah;
Query OK, 1 row affected (0.00 sec)
```

```sql
mysql> USE sekolah;
Database changed
```

```sql
mysql> CREATE table sekolah(nis INT(10), nama VARCHAR(20), alamat VARCHAR(50) ); 
Query OK, 0 rows affected (0.02 sec)
```
