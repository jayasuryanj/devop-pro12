![68747470733a2f2f696d6775722e636f6d2f5570366b3255662e706e67](https://github.com/jayasuryanj/devop-pro12/assets/102530365/4dda4542-7fc7-419a-9a5c-90bf881e23be)
## Java Login App ##
Testing 

## Sample Java Login application uses "UserDB" database and Table schema to store the Employee Login details. ##

## How to see list of Databases ##
SHOW DATABASES;

## How to create Database ##

CREATE DATABASE UserDB;

## How to list Tables ##

USE UserDB;

SHOW TABLES;

## How to create Table ##
## Below Query to create require TABLE schema to store Employee records ##

CREATE TABLE Employee (
  id int unsigned auto_increment not null,
  first_name varchar(250),
  last_name varchar(250),
  email varchar(250),
  username varchar(250),
  password varchar(250),
  regdate timestamp,
  primary key (id)
);

## List Table data ##
SELECT * FROM Employee;

## Describe Table schema ##
DESCRIBE Employee;
