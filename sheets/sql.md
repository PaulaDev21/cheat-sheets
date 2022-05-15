# Cheat Sheet for SQL commands
** Created by: ** [Ana Paula B. Lopes](https://github.com/PaulaDev21)

## DDL commands

Create a database
	SQL CREATE DATABASE <DB name>;

Create a table
Ref: [Data types](https://www.journaldev.com/16774/sql-data-types)

	CREATE TABLE dummyEntity (
    		entity_id INT UNIQUE AUTO_INCREMENT,
    		string_field VARCHAR(255),
    		date_field DATE,
    		dt_field DATETIME,
    		ts_field TIMESTAMP,
    		categorical_field ENUM('cat1', 'cat2'),
    		numerical_fiels float, 
    	PRIMARY KEY (entity_id)
	);
		

# References
- [Data types](https://www.journaldev.com/16774/sql-data-types)