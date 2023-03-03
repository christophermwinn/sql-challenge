# sql-challenge
Module 9 Challenge

Attached are the files for the sql challenge:
- data model
- sql file of the table schema
- sql file of the requested queries

This took some trial and error to get the tables built correctly.  The data model was very useful, and I discovered the export feature which produced the schema in PostgreSQL format.  Running the code revealed some errors I made in data type, which were easily corrected.  I had to add a sequential field to the dept_emp table to serve as a primary key, as the employee number was not unique (one duplicate).  The other trouble I had was importing the tables in the correct order.  For instance, the department table had to be imported before department manager or department employee because of the relationship of the foreign keys.

The actual queries were more straightforward; the main difficulty was determining what kind of join was needed.
