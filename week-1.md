# Week 1 Paper

By Chris Blount
9/18/2021

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
I did a lot of searching to try and find specific reasons the MySQL command line shell makes you productive. I didn't find anything on the topic of MySQL command line adding to productivity. However, as a frequent command line user for Git, I can attest that my workflow speed is definitely increased by using the command line instead of a GUI. 

During my command line productivity search, I came across a Medium article with some tips to make your command line workflow even faster. My favorite tip from the article is how to make aliases. Here's the Git example from the article: `3`
```
alias gs="git status"
alias gp="git pull"
alias gb="git branch"
alias ga="git add ."
```
I'm sure aliases could come in handy for any command line work, including MySQL.

###### What is the difference between using an IDE and the CLI?
An integrated development environment (IDE) is a software application that enables software developers to create software. IDEs have a number of features useful to developers - such as: source code editor, build automation tools, and a debugger. `4`

A command-line interface (CLI) responds to text commands made in a terminal window. CLIs are different than IDEs but are still very useful to software developers. I use CLIs to spin up new software development projects, to install software packages, and even inside IDE terminal windows to run Git commands.

###### References:
1. *Learning SQL, 3rd Edition* - By Alan Beaulieu
1. *[Databases: Evolution and Change](https://medium.com/@rpolding/databases-evolution-and-change-29b8abe9df3e)* - By Robert Polding, PhD
1. *[3 Terminal Commands to Increase Your Productivity](https://betterprogramming.pub/3-terminal-commands-to-increase-your-productivity-9dbab9f1a015)* - By Pankaj Gupta
1. [Integrated development environment](https://en.wikipedia.org/wiki/Integrated_development_environment) - Wikipedia