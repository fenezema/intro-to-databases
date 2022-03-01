# NoSQL

## What is?
NoSQL a.k.a `Not only SQL` is the new type of database that, basically not relational. What this mean is that, there are no predefine structure for spesific database. Most of the time, the query language for NoSQL databases are different than SQL. 

## Features
Each NoSQL database has its own unique features. At a high level, many NoSQL databases have the following features:
1. Flexible schemas
2. Horizontal scaling
3. Fast queries due to the data model
4. Ease of use for developers

## Types
There are a few types of NoSQL databases. These are:
1. Document databases store data in documents similar to JSON (JavaScript Object Notation) objects. Each document contains pairs of fields and values. The values can typically be a variety of types including things like strings, numbers, booleans, arrays, or objects.
2. Key-value databases are a simpler type of database where each item contains keys and values.
3. Graph databases store data in nodes and edges. Nodes typically store information about people, places, and things, while edges store information about the relationships between the nodes.
4. Others :)
The one we will dive (but not too deep) for this section is the document type database, while the next section would be Key-Value and Graph Databases.

## Query Language
While most of RDBMS shared the same syntax almost every time, some NoSQL does not. Some, like ArangoDB has query language that looks almost like a programming language that relies on looping, while MongoDB query languge looks like how we access object properties and methods like how we do it in every programming language.

But there are some similarities between them, both query language looks like a programming language in mind.

This is basically almost related to `Point 4` in **## Features** section earlier. The ease of use for developers mainly because of the nature of NoSQL itself. Because that we don't need to define the DB structure beforehand, developers can develop app faster(in some cases), and with the nature of the query language, developers won't need to familiarize themself with new language, eventhough in reality, most of use are already familiar with SQL, while the query language for NoSQL, well, sometimes different than other NoSQL query language.

## Examples
There are many examples of Document type NoSQL databases. Some of them are MongoDB, Cassandra, ArangoDB, etc. <br>
The one we heard the most probably MongoDB, and Cassandra. While ArangoDB, well, it has it perks that, it has Document type, Graph, Edge on its engine itself. So, we can exactly categorize it into one category.

## Tools
Again, each has it owns tool for accessing the Database, while there are tools that capable of connecting to any database, even RDBMS or NoSQL, in one app. The example would be TablePlus (again, not recommended on Linux and its derivatis. Beta version still lacks of features)