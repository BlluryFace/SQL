## Read operation
### Read all values of a column in a table
* SELECT * FROM table_name;
### Read all values of a specific column
* SELECT column_name FROM table_name;
### Read all values of many column
* SELECT column_name1, columns_name2 FROM table_name;
### Show values in column that match a value
* SELECT column_name FROM table_name WHERE reference_column = value;
### Show a column with a temporary name
* SELECT column_name AS desired_name FROM table_name;
## Update operation
### Update values in a table
* UPDATE table_name SET desired_column = changed_value WHERE reference_column = reference_value;
Ex: UPDATE dogs SET age = -9999999 WHERE name='I Hate You';\
Note: check if there is any duplicate value for the reference_value
## Delete operation
### Delete a specific value
* DELETE FROM table_name WHERE desired_column=desired_value;
### Delete all rows in a table
* DELETE FROM table_name;