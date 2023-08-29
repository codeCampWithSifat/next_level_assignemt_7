# next_level_assignemt_7 PostgreSQl Interview Question

<br>
<h2>What is PostgreSQL?</h2>
<p>PostgreSQL is an object-relational database management system (ORDBMS) based on POSTGRES,PostgreSQL is an open-source descendant of this original Berkeley code. It supports a large part of the SQL</p>

</br>

<h2>What is the purpose of a database schema in PostgreSQL?</h2>
<p>In PostgreSQL Schema, the critical advantage is that a database can have the same table name if it belongs to different schemas</p>
</br>

<h2>Explain the primary key and foreign key concepts in PostgreSQL?</h2>
<p><strong>Primary Key</strong> : A primary key is used to ensure data in the specific column is unique.</p>
<p><strong>Foreign Key</strong>: A foreign key is a column or group of columns in a relational database table that provides a link between data in two tables.</p>
</br>

<h2>What is the difference between the VARCHAR and CHAR data types?</h2>
<p>CHAR: This data type is used to store characters of limited length. It is represented as char(n) or character(n) in PostgreSQL, where n represents the limit of the length of the characters</p>
<p>This data type is used to store characters of limited length. It is represented as varchar(n) in PostgreSQL, where n represents the limit of the length of the characters. If n is not specified it defaults to varchar which has unlimited length.</p>

</br>
<h2>Explain the purpose of the WHERE clause in a SELECT statement</h2>
<p>The PostgreSQL WHERE clause is used to specify a condition while fetching the data from single table or joining with multiple tables. If the given condition is satisfied, only then it returns specific value from the table.</p>
 </br>

 <h2>What are the LIMIT and OFFSET clauses used for?</h2>
 <p>The LIMIT clause is used to restrict the number of rows returned by a query. The OFFSET clause is used to skip the number of rows in the resultset of a query.</p>
 </br>

 <h2>How can you perform data modification using UPDATE statements<h2>
 
 <p>specify the name of the table that I want to update data after the UPDATE keyword. Second, specify columns and their new values after SET keyword. The columns that do not appear in the SET clause retain their original values. Third, determine which rows to update in the condition of the WHERE clause</p>

 </br>

<h2>What is the significance of the JOIN operation, and how does it work in PostgreSQL?<h2>

<p>A PostgreSQL Join statement is used to combine data or rows from one(self-join) or more tables based on a common field between them. These common fields are generally the Primary key of the first table and Foreign key of other tables. There are 4 basic types of joins supported by PostgreSQL, namely: Inner Join , Left Join , Right Join, Full Join And The Other Are Cross Join</p>
</br>

<h2>Explain the GROUP BY clause and its role in aggregation operations?</h2>
<p>The GROUP BY clause groups rows that have the same values into summary rows, like "find the number of customers in each country". The GROUP BY clause is often used with aggregate functions like COUNT() , MAX() , MIN() , SUM() , AVG(),Count(*) to group the result-set by one or more columns.</p>

</br>
<h2>How can you calculate aggregate functions like COUNT, SUM, and AVG in PostgreSQL?</h2>

<p>Count: select Count(*) From students</p>
<p>Sum : select Sum(salary) from employees</p>
<p>AVG: select AVG(age) from students</p>

</br>

<h2>What is the purpose of an index in PostgreSQL, and how does it optimize query performance?</h2>
<p>Indexes are a common way to enhance database performance. An index allows the database server to find and retrieve specific rows much faster than it could do without an index. But indexes also add overhead to the database system as a whole, so they should be used sensibly.</p>

</br>

<h2>Explain the concept of a PostgreSQL view and how it differs from a table?</h2>
<p>View and Table both are integral parts of a relational database, and both terms are used interchangeably. The view is a result of an SQL query and it is a virtual table, whereas a Table is formed up of rows and columns that store the information of any object and be used to retrieve that data whenever required.</p>