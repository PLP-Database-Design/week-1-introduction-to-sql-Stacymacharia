1. State and Explain the components of a DBMS(Database Management System)
Database Engine: The core service for storing, managing, and retrieving data. It interprets and executes queries.

Database Schema: The blueprint of the database that defines its structure, including tables, relationships, and constraints.

Query Processor: Interprets and executes SQL queries, converting them into commands that the database engine can understand.

Database Manager: Manages access to the database, ensuring data integrity and controlling concurrent access.

Transaction Manager: Ensures that database transactions are processed reliably and follows the ACID (Atomicity, Consistency, Isolation, Durability) properties.

Security and Integrity Manager: Manages security aspects like user authentication, data access control, and integrity constraints (such as uniqueness and referential integrity).

User Interface: Allows users to interact with the DBMS, often through a front-end application or query interface.

2. What is a relational database? Give 4 examples.
A relational database organizes data into tables (relations) that consist of rows and columns, with each table having a primary key to uniquely identify records. 
These tables are related to one another through foreign keys, enabling efficient querying and data management.

Examples:

MySQL
PostgreSQL
Oracle Database
Microsoft SQL Server

3. State and Explain three classifications of SQL?
Data Definition Language (DDL): Used for defining and modifying the structure of database objects, such as tables and schemas. Examples: CREATE, ALTER, DROP.
Data Manipulation Language (DML): Used for retrieving and manipulating data within the tables. Examples: SELECT, INSERT, UPDATE, DELETE.
Data Control Language (DCL): Used for defining access control and permissions on database objects. Examples: GRANT, REVOKE.

4. What is the difference between a Primary Key and a Foreign Key?
Primary Key: A unique identifier for a record in a table. It ensures that no two records have the same value for the primary key column(s).
Foreign Key: A column in one table that refers to the primary key in another table, establishing a relationship between the two tables.

5. What is an Entity-Relationship Diagram?
An Entity-Relationship Diagram (ERD) is a graphical representation of entities (objects) in a database and their relationships. 
It visually models the data structure, showing entities, their attributes, and the relationships between them (e.g., one-to-many, many-to-many).



6. What are the advantages of relational databases?
Data Integrity: Ensures accuracy and consistency of data through constraints like primary keys and foreign keys.
Scalability: Can handle large volumes of data and complex queries.
Flexibility: Allows for easy updates, deletions, and modifications without affecting other data.
Normalization: Reduces redundancy and dependency by organizing data into multiple related tables.
Security: Provides robust security features, including access control and data encryption.

7. State four types of data type used to store data in tables?
Integer: Used for storing whole numbers.
Varchar (or String): Used for storing variable-length text.
Date: Used for storing date values (e.g., 2024-11-27).
Boolean: Used for storing binary values (true/false).
   
8. What is the purpose of a database management system (DBMS)? 
The purpose of a DBMS is to provide a systematic and efficient way of managing, storing, retrieving, and manipulating data.
It ensures data integrity, security, and consistency while offering a platform for users and applications to interact with the database easily.
A DBMS also helps in handling large amounts of data, enabling concurrent access, and supporting transactions.