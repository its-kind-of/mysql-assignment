# mysql-problems
1. create a database called 'assignment' (Note please do the assignment tasks in this database)
2. Create the tables from ConsolidatedTables.sql and enter the records as specified in it.
3. Create a table called countries with the following columns name, population, capital <br>
- choose appropriate datatypes for the columns br>
> a. Insert the data into the table <br>
> b) Add a couple of countries of your choice <br>
> c) Change ‘Delhi' to ‘New Delhi' <br>

4. Rename the table countries to big_countries .
5. Create the following tables. Use auto increment wherever applicable <br>
> a. Product <br> 
> product_id - primary key <br>
> product_name - cannot be null and only unique values are allowed <br>
> description <br>
> supplier_id - foreign key of supplier table <br>
b. Suppliers <br>
> supplier_id - primary key <br>
> supplier_name <br>
> location <br>
c. Stock
id - primary key
product_id - foreign key of product table
balance_stock
6. Enter some records into the three tables.
7. Modify the supplier table to make supplier name unique and not null.
8. Modify the emp table as follows <br>
> a. Add a column called deptno <br>
> b. Set the value of deptno in the following order <br>
> deptno = 20 where emp_id is divisible by 2 <br> 
> deptno = 30 where emp_id is divisible by 3 <br>
> deptno = 40 where emp_id is divisible by 4 <br>
> deptno = 50 where emp_id is divisible by 5 <br>
> deptno = 10 for the remaining records.<br>
9. Create a unique index on the emp_id column.
10. Create a view called emp_sal on the emp table by selecting the following fields in the
order of highest salary to the lowest salary.
emp_no, first_name, last_name, salar

