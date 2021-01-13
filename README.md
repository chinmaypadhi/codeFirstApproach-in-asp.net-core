# codeFirstApproach-in-asp.net-corecreate poco clas
create dbcontextclass


go to the manage console and wirte the command to start migration
(1)add-migration <provide any name for migration>

then we have to write update database command (if you have one database then no need to write the database name otherwise you must have to write the database name ) 
(2)update-database <database name>

now the database will created  successfully
if you want to  create any modification on your data then we need to write the following command
(3)add-migration addedsalary
here in the above command we can add any migration name instead od addsalary

(4)update-database addedsalary


-------------------------------------------------------------------------------------------
link
https://www.c-sharpcorner.com/article/code-first-approach-in-asp-net-core-mvc-with-ef-core-migration/
