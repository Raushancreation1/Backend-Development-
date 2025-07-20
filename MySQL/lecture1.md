SHOW DATABASES;
//to show all the databases available on your system.

USE <database name>;
//to select a particular database To run queries on 

SHOW TABLES;
//To list down all the of a particular selected database

CREATE DATABASE <name>;
//to create a new database

CREATE TABLE <name> {
    <column name 1> [datatype],
    <column name 2> [datatype],
    .
    .
}; 

//To create a new table


DESC <table name>;
//show structure and description of the table



INSERT INTO <table name> (col1, col2, ....) VALUES (<value 1>, <value 2>, ...)