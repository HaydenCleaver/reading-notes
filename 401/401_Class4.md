# Class 4

Now that we're really working with SQL it's good to revisit what we learned about it and NoSQL in 301.  Having worked with it a little bit, it's easier to understand more of what I'm reading about.

## SQL vs NoSQL

1. SQL is better for intensive and complex search queries since it's so strictly organized and structured.

2. NoSQL is better for hierarchal searches because of the way that it stores things in key-value pairs.

3. Scalability for the two types of database is different.  In the case of SQL, increasing the CPU, RAM, or SSD on a server can improve its viability. NoSQL can be scaled up by adding servers to help with the search load.

    [thegeekstuff](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

## SQL Modeling Techniques

1. A "one to many" relationship simply describes that one entry may belong to many other entries on another table.

2. Prior to designing your relational database, it might be useful to create a diagram of the database tables and their relationships.

3. Primary keys uniquely identify the rows in a table, and typically only have one per.  Foreign keys are a column or several columns that match a primary key from a different table.

    [essentialSQL](https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/)

## SQL vs NoSQL part II

1. Keywords are predefined terms in SQL that allow the user to identify their data needs when querying an SQL database.  Parameters exchange data between procedures and applications that they're stored on.

2. Normalization is essentially the practice of making the database more effiecient and easier to use by reducing reduncies and making relationships that make sense.

3. One-to-one relations describe entries on a table that only link to one entry on another table, and vice-versa. One-to-many relationships describe an entry on one table that links to many other entries on other tables.  Many-to-many relationships describes multiple entries that link to multiple entries on other tables.

[Return to Table of Contents](https://haydencleaver.github.io/reading-notes/)