# Relational Database

## What is?
Relational Database are the databases that we (possibly) know first and the one that basically we learn first at college. In a very short term, a relational database is the one where the structure of the database is defined pre-development, whether it's the structure of the tables of one database, the indexes, and others. 

## Query Language
Most Relational Databases use the Structured Query Language or SQL as we know it. Most of the time, SQL provides the same syntax, whatever the RDBMS are. 

The query itself is pretty straighforward in term of syntax and readibility. The are many courses and tutorial about this now a days for SQL, whether it is a paid tutorial, like Udemy, Coursera, etc, or even the free one like, YouTube for example. 

As mentioned earlier, whatever the RDBMS we use, the SQL would be the same in so many ways. But that does not mean that every thing is the same top bottom. Sometimes there are traits that only one RDBMS has, while other RDBMS does not. But the whole idea, the general ways, will the same.

Some example of SQL Queries we see every day<br>
`select * from amazing_table_name;` <br>
`select` indicating that the operation we do is basically querying and get data from the database<br>
`*` indicates that we want to get all the columns the table has<br>
`amazing_table_name` indicates the table name we just queried.

Of course this is the simplest example we can do in term of querying to database. Let say that if we want to add condition to that query instead of getting all the data the table has, we can add condition with syntax `where <condition>`. 

The condition can be anything. Most of the time, it will be comparison. <br>
Let's say we have a **User table, named `users`** with columns as follows:
1. id
2. name
3. address
4. phone

Let's say we want to get a user with phone number `081232454676`
We can achieve this by using this query
`select id, name, address, phone from users where phone = '081232454676';`<br>
Pretty simple and straightforward right?
You can also check for other comparison methods.

Not just that, there also other operations we can do in SQL, like join, where we can, as it says, join one table to the other table, etc.

## ACID
Four crucial properties define relational database transactions: atomicity, consistency, isolation, and durability—typically referred to as ACID.
1. Atomicity defines all the elements that make up a complete database transaction.
2. Consistency defines the rules for maintaining data points in a correct state after a transaction.
3. Isolation keeps the effect of a transaction invisible to others until it is committed, to avoid confusion.
4. Durability ensures that data changes become permanent once the transaction is committed.

## Examples
There are many examples for RDBMS. Probably the one we heard all the time would be MySQL, or PostgreSQL. These two relational db are the most famous one. These relational databases are the one that maintained by the community, or we can say, that it is open source. There is also SQLite, that we can say is the most simple one. No tilitale when installing the tools, it's super straightforward. 

Other examples would be Oracle, the non open-source one, that basically maintained by a company, etc.

The example will be pretty much scattered online. Pretty easy to find.

## Tools
Now, there are many tools that we can use to connect and query to a database.<br>
If you are familiar with LAMPP, or XAMPP (the Windows version), you must be familiar with PHPMyAdmin, the tool that ships with XAMPP, to access MySQL database. There is also MySQL Workbench. <br>
For PostgreSQL, the famous one will be PGAdmin. It's like the unspoken consensus. But if you are a terminal guy, you can always choose to use psql.

But aside from those tools that spesific for one type of Database, there are tools that basically can connect with anything, even the non-relational/nosql or the key-value db one (will be explain later). There are DBeaver, or TablePlus (the Mac one, the Beta version on Linux is very limited to be honest. Consider using other tool), etc.