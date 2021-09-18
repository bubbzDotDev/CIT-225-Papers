# Week 1 Paper

By Chris Blount
9/17/2021

###### Non-relational:
-	**Hierarchical database system:** Data represented as one or more tree structures. Each node in the tree may have either zero or one parent and zero, one, or many children. This is known as single-parent hierarchy. `1`
-	**Network database system:** Exposes sets of records and sets of links that define relationships between different records. Records can be accessed from multiple places, allowing network databases to act as multiparent hierarchies. `1`

The main difference between the two is that the network model allows each record to have more than one parent and child record. `2`

###### Relational:
Dr. E. F. Codd, of IBM's research lab, published a paper in 1970 proposing data be represented in tables. Each table includes information uniquely identifying rows in that table (known as primary keys). Additional information is included to describe the entity completely. Tables can also include information to navigate to other tables. Foreign keys are unique identifiers of primary keys from other tables. `1`

###### How relational databases evolved from networked and hierarchical databases:
Hierarchical database model solved many of the problems of a paper-based system. The network model overcame restrictions of the hierarchnical model, but it didn't become dominant. This is because IBM continued to use the hierarchical model for its more established products and researchers developed the relational model only a year after the network model was described in a publication released by scientists in 1969. The relational model was much easier for designers to understand and the programming interface was an improvement. The relational model didn't become popular until advances in computing in the 1980s. `2`

###### Do the following:

- [x]	Install a MySQL database on your desktop.
- [x]	Create a database from the assigned Learning SQL textbook.
- [x]	Populate the model.

###### Why does the MySQL command line shell make you more productive?
asdf

###### What is the difference between using an IDE and the CLI?
asdf

###### References:
1. *Learning SQL, 3rd Edition* - By Alan Beaulieu
1. *[Databases: Evolution and Change](https://medium.com/@rpolding/databases-evolution-and-change-29b8abe9df3e)* - By Robert Polding, PhD
