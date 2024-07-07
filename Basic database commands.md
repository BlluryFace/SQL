Note: the semicolon signify the end of a SQL command and start the execution of such command \
SQL dont care about new line but care about space between words
### Show databases
* show databases;
### Create database
* CREATE DATABASE 'name';
### Delete database
* DROP DATABASE 'name';
### Delete table
* DROP TABLE 'name';
### Choose a database to use
* USE 'name';
### Check the name of a database
* SELECT database();
### Create a table WITH column
* CREATE TABLE 'name' (column1 data_type, column2 data_type);
* Ex: CREATE TABLE Dogs (Name VARCHAR(10), Bred VARCHAR(5), ID INT);
### Show all tables in a databases
* SHOW TABLES;
### Show all fields in a table
* SHOW COLUMNS FROM 'name';
* DESC 'name';
* DESCRIBE 'name';
### Comments
* --