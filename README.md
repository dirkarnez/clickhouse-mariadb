clickhouse-mariadb
==================
### MariaDB, [MySQL | ClickHouse Documentation](https://clickhouse.tech/docs/en/engines/database-engines/mysql/)
1. [ClickHouse Query](http://localhost:8123/play)
2. `CREATE DATABASE mysql_db ENGINE = MySQL('mariadb:3306', 'default', 'root', '123456')`
3. `SHOW DATABASES`
4. `SELECT * FROM mysql_db.mysql_table`
5. `INSERT INTO mysql_db.mysql_table VALUES (3,4)`
6. `SELECT * FROM mysql_db.mysql_table`
