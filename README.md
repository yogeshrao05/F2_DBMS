# F2_DBMS
# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 


### OUTPUT:
![output](https://github.com/AdhithiyanK/F2_DBMS/assets/121029258/e93b8c68-6103-4c3d-bc79-41a19c7c39fb)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 

### OUTPUT:
![op](https://github.com/AdhithiyanK/F2_DBMS/assets/121029258/a453dd1d-90a3-498b-8f49-4f8c956c6ac1)


### 3) Drop the student table
 
### SQL QUERY: 

 ### OUTPUT:
 ![op1](https://github.com/AdhithiyanK/F2_DBMS/assets/121029258/7166c862-ebdd-43f2-9ac7-b5d2a15d9710)



### 4) Delete the student table using truncate keyword

### SQL QUERY: 


### OUTPUT:

![op2](https://github.com/AdhithiyanK/F2_DBMS/assets/121029258/c1e91078-ebe7-4df9-9d5c-ec7d5751585b)


### 5) Rename the student table to mystudent

### SQL QUERY: 


### OUTPUT:
![op3](https://github.com/AdhithiyanK/F2_DBMS/assets/121029258/68d2f1b4-71f0-42af-95d6-d56481e4675a)
