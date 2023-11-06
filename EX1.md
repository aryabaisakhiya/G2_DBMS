# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

##Date:


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
```
create table student(rollno int,name char(20),age int,addr varchar(20),phoneno int);

```
### OUTPUT:
![image](https://github.com/aryabaisakhiya/G2_DBMS/assets/119393645/37409832-0fa2-41a5-bd73-722cefc18172)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student add department char(30);

```
### OUTPUT:
![image](https://github.com/aryabaisakhiya/G2_DBMS/assets/119393645/1da62af1-2eb6-46ee-8329-df34c79510c3)


### 3) Drop the student table
 
### SQL QUERY: 
```
drop table student;

```
### OUTPUT:
![image](https://github.com/aryabaisakhiya/G2_DBMS/assets/119393645/1f22489a-cb0a-40e8-a939-c722fc12257e)



### 4) Delete the student table using truncate keyword
### SQL QUERY: 
```
truncate table student;

```
### OUTPUT:
![image](https://github.com/aryabaisakhiya/G2_DBMS/assets/119393645/b11b169f-2eef-488c-b9f5-654b17f8571b)


### 5) Rename the student table to mystudent
### SQL QUERY: 
```
alter table student rename to mystudent;

```
### OUTPUT:
![image](https://github.com/aryabaisakhiya/G2_DBMS/assets/119393645/a2aa3686-d4b5-417a-a642-4506ba3f6864)


### RESULT:
To create a student database and execute DDL queries using SQL is executed successfully.
