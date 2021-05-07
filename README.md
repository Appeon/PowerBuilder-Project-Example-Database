# <b>Sample Database Readme</b>

This repository provides the example database files necessary for setting up the database to work with PowerBuilder Demo, such as [PowerBuilder-Graph-Example](https://github.com/Appeon/PowerBuilder-Graph-Example) and [PowerBuilder-Sales-Example](https://github.com/Appeon/PowerBuilder-Sales-Example). 

### Supported database versions 

- AppeonSample_for_sqlanywhere: SQL Anywhere 16 or later
- pbdemo2021_for_sqlanywhere: SQL Anywhere 16 or later
- pbpostgres_for_postgresql: PostgreSQL 10 or later

### Steps to restore AppeonSample_for_sqlanywhere

1. Find the dbsrv17.exe file in the Bin64 folder of the SQL Anywhere 17 installation directory;
2. Run dbsrv17.exe and load AppeonSample.db.

### Steps to restore pbdemo2021_for_sqlanywhere

1. Find the dbsrv17.exe file in the Bin64 folder of the SQL Anywhere 17 installation directory;
2. Run dbsrv17.exe and load pbdemo2021.db.

### Steps to restore pbpostgres_for_PostgreSQL

1. Start pgAdmin;
2. Create a new database pbpostgres within the server you are using; 
3. Right click the database and choose Restore; 
4. Use the Browser button to select the database backup file pbpostgres.dmp;
5. Select Restore to start restoring the database.
