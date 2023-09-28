#EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS:
## AIM:
To create a student database and execute DDL queries using SQL.
## DDL (Data Definition Language).
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
## List of DDL commands:
### CREATE:
his command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers). DROP: This command is used to delete objects from the database. ALTER: This is used to alter the structure of the database.
### TRUNCATE:
This is used to remove all records from a table, including all spaces allocated for the records are removed. RENAME: This is used to rename an object existing in the database.
## Query:
1) Create a table student with the following fieds rollno,name,age,address,phoneno.
## SQL QUERY: 
# OUTPUT:
create table student(rollno int,name char(20),age int,addr varchar(20),phoneno int);
![image](https://github.com/Jeevithaelumalai/G2_DBMS/assets/118708245/04159bcd-7e7e-498c-92b6-a0cf49f97014)
## SQL QUERY:
### alter table student add department char(30);
2) Change the above student table by adding another attribute department
![image](https://github.com/Jeevithaelumalai/G2_DBMS/assets/118708245/efb61fb6-0680-43b8-992a-3553dc9f2970)
## SQL QUERY:
### drop table student;

![image](https://github.com/Jeevithaelumalai/G2_DBMS/assets/118708245/e5e5796b-5164-46cf-bc28-d745c9c00240)
### truncate table student;

![image](https://github.com/Jeevithaelumalai/G2_DBMS/assets/118708245/7c7b3c48-3e22-4cfd-afd0-a8352cd453b5)
### alter table student rename to mystudent;

![image](https://github.com/Jeevithaelumalai/G2_DBMS/assets/118708245/e51ca246-2e5c-4819-a327-efa3a0ad9db7)
# RESLT:
To create a student database and execute DDL queries using SQL is executed successfully.
