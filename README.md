<h1 align="center">MySql</h1>
 
 
## Data Definition Language (DDL) commands of MySQL:

1. **CREATE:** Used to create a new table, database, or view

   ```bash
   CREATE DATABASE database_name;
   CREATE TABLE table_name;
   ```

2. **Alter:** Used to modify the structure of an existing table


   ```bash
   ALTER TABLE table_name 
   ADD column_name datatype;
   
   ALTER TABLE table_name 
   DROP column_name;
   
   ALTER TABLE table_name 
   MODIFY column_name datatype;

   ```
  
3. **Drop:** Used to delete a table, database, or view

   ```bash
   DROP TABLE table_name;
   DROP DATABASE database_name;
   DROP VIEW view_name;
   ```
   
4. **Truncate:** Used to remove all data from a table


   ```bash
   TRUNCATE TABLE table_name;
   ```
