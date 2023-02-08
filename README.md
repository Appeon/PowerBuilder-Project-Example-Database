# <b>Sample Database Readme</b>

This repository provides the example database files necessary for setting up the database to work with Appeon demos, such as [PowerBuilder-Graph-Example](https://github.com/Appeon/PowerBuilder-Graph-Example) and [PowerBuilder-Sales-Example](https://github.com/Appeon/PowerBuilder-Sales-Example). 

### Supported database versions 

- AppeonSample_for_sqlanywhere: SQL Anywhere 16 or later
- pbdemo2021_for_sqlanywhere: SQL Anywhere 16 or later
- pbdemo2021_for_postgresql: PostgreSQL 10 or later
- pbdemodb_for_sqlserver: SQL Sever 2016 or later

### Steps to restore AppeonSample_for_sqlanywhere

1. Find the dbsrv17.exe file in the Bin64 folder of the SQL Anywhere 17 installation directory;
2. Run dbsrv17.exe and load AppeonSample.db.

### Steps to restore pbdemo2021_for_sqlanywhere

1. Find the dbsrv17.exe file in the Bin64 folder of the SQL Anywhere 17 installation directory;
2. Run dbsrv17.exe and load pbdemo2021.db.

### Steps to restore pbdemo2021_for_PostgreSQL

1. Start pgAdmin;
2. Create a new database pbpostgres within the server you are using; 
3. Right click the database and choose Restore; 
4. In the Restore screen, select "Custom or Tar" as the format, and "Postgres" as the Role Name;
5. Use the Browser button to select the database backup file pbpostgres.dmp;
6. Select Restore to restore the database. Note that during the process, an error message may appear that indicates public already exists in schemas. Please ignore this error, as it will not affect the restoration.

### Steps to restore pbdemodb_for_sqlserver

1. Open SQL Server Management Studio and connect to the target SQL Server instance.
2. Right-click on the Databases node, and select Restore Database.
3. On the General page, use the Source section to specify the source and location of the backup database (pbsqlserver.bak) to restore.  
4. In the Destination section, the Database box is automatically populated with the name of the database to be restored. To change the name of the database, enter the new name in the Database box, for example, PBDemoDB2022.
5. Click **OK**. This will initiate the database restore. After it completes, you will have the PBDemoDB2022 database installed on your SQL Server instance.
