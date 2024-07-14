### Insert a data 
```INSERT INTO table_name (column_name) VALUES (value);```
### Show all data in a table
```SELECT * FROM table_name;```
### Insert multiple data 
```INSERT INTO table_name (column_name) VALUES (value1),(value2),(value3),(value4);```
### Create a column that can take NUll value
```CREATE TABLE table_name (column_name data_type NOT NULL);```
### Quotes rule
* Always use single quote for text 
* Double quote inside single quote will be registered as normal string
* Use ```/'``` to register single quote as string
### Adding default value
```CREATE TABLE table_name (column_name data_type DEFAULT default name); ```
* Note: No need to define table as NOT NULL. 
The table will automatically fill in the missing data with the default value
### Primary key
* An unique identifier for each value in a table\
```CREATE TABLE table_name (id_name INT PRIMARY KEY);```\
With Auto increment: ```CREATE TABLE table_name (column_name INT AUTO_INCREMENT PRIMARY KEY );```
