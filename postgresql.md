# Install postgresql on ubuntu 16.04

What is Postgresql?
--------
PostgreSQL is a Relational Database Management system which store, retrieves the information from the Postgresql Database.

Install PostgreSql
--------
- `$ sudo apt-get update`
- `$ sudo apt-get install postgresql postgresql-contrib`
- `$ sudo -u postgres psql postgres`
- postgres=# `\password postgres`
- Enter new password: `******`
- Enter it again: `*****`
- Exit psql: `\q`

Install PgAdmin4
---------------
- [Download](https://www.pgadmin.org/download/pgadmin-4-python-wheel/)
- Unzip the zip file.
- `cd pgsql/pgAdmin 4/bin`
- Click on `pgAdmin4`. It will open an interface on browser (http://127.0.0.1:43911/browser/).
- Create connection
![PgSql Connection](images/pg-connect.png)

** Enjoy **



