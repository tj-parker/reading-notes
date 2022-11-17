# Class 11 Reading Notes

## nosql vs sql

| SQL | NoSQL |
| --- | ----- |
| Relational Databases | Non-relational database |
| table based | document based |
| predefined schema | dynamic schema |
| vertically scalable | horizontally scalable |
| use SQL for defining and manipulating data | focused on collection of documents, syntax varies |

SQL databases are a good fit for the complex query intensive environment, such as heacy duty transactional type applications

NoSQL is best for hierarchical data storage as it follows the key-value pair way or storing data similar to JSON data

SQL databases are vertically scalable, increasing load management comes from increasing the specifications of the server. NoSQL databases are horizontally scalable, increase the number of servers to manage increasing load

SQL stands for structures query language

A relational database is a database that works with certain assumptions, such as with a table

A schema is a strict requirement for which data can go into a table

A NoSQL database like MongoDB store documents and don't have to use the same schema or relations

The downside is that all the data may not adhere to the same format, but it is more flexible becuase of this reason
