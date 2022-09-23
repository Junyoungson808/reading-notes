# Reading

## [nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

1. What type of database is the best fit for the complex query intensive environment?
    - SQL databases are good fit for the complex query intensive environment
2. What type of database is the best fit for hierarchical data storage?
    - NoSQL database fits better for the hierarchical data storage as it follows the key-value pair way of storing data similar to JSON data. NoSQL database are highly preferred for large data set (i.e for big data). Hbase is an example for this purpose.
3. Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.
    - SQL are vertically scalable, you can increase load by increasing CPU, RAM, SSD, on a single server. While NoSql are horizontally scalable. You can just add more servers to your database.

## [sql modeling techniques](https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/)

1. Among data tables, what is a one-to-many relationship and how do we “relate” them? 
    - entry in one table can be related to more than one entry in another.
2. Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.
3. Explain the difference between a primary and foreign key.
Primary key = uniquely identify each row in a table, (table has one primary key, but can have more.) 
Foreign Key = Column or Set of Colums that match primary key in a another table

### [sql vs nosql](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)

1. How do we treat keywords and parameters differently in SQL syntax?
    - ??
2. Define normalization within the context of schemas and data.
    - normalization allows the database to be 
3. Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.
    - one entry equals to one colum/row, one entry can relate to many rows/colums in a data table, and many entrys have many relate to many colums/rows in many tables.

#### Bookmark and Review

[sequelize api](https://sequelize.org/master/)