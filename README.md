# northwind.py
1. In the Northwind database, what is the type of relationship between the `Employee` and `Territory` tables?
- In the Northwind database, there is many-to-many relationship between the 'Employee' and 'Territory' tables. 
- Each employee can be linked to multiple territories.
- Each territory can be linked to multiple employees.

2. What is a situation where a document store (like MongoDB) is appropriate, and what is a situation where it is not appropriate?
- Big volume of unstructured data can be  stored in MongodB.
- The documents which doesn't need to have a schema defined beforehand can be stored in MongoDB.
- Mongodb is not relational so we lose all the capabilities of relational database.
- JOINS on data are not supported so we cannot use Mongodb were JOIN is required.
- MongoDB does not provide Atomicity, Consistency, Isolation, Durability.

3. What is "NewSQL", and what is it trying to achieve?
- NewSQL is a new database access language being promoted as superior SQL. 
- NewSQL databases have the same performances as NoSQL systems.
- NewSQL provide Administrators with Atomicity, Consistency, Isolation, Durability. 
- It provides the scalability and performance of NoSQL with the reliability of SQL.

- 
