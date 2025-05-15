# **Phase 1: Get Comfortable with PostgreSQL Basics (1–2 weeks)**

**Goal:** Bridge the gap from SQL Server to PostgreSQL.

**Topics to Cover:**

* PostgreSQL architecture and differences from SQL Server
* Data types, functions, and operators
* Writing queries: SELECT, JOINs, subqueries, etc.
* DDL & DML basics (CREATE, ALTER, INSERT, UPDATE, DELETE)
* Indexing and performance tuning basics
* Transactions and isolation levels

**Resources:**

* [PostgreSQL Tutorial](https://www.postgresqltutorial.com/)
* [Mode Analytics SQL Tutorial (PostgreSQL flavor)](https://mode.com/sql-tutorial/)
* Book: *PostgreSQL: Up and Running* by Regina O. Obe & Leo S. Hsu

### What is PostgreSQL

PostgreSQL is an advanced, enterprise-class, and open-source relational database system. PostgreSQL supports both SQL (relational) and JSON (non-relational) querying.

PostgreSQL is a highly stable database backed by more than 20 years of development by the open-source community.

PostgreSQL is used as a primary database for many web applications as well as mobile and analytics applications.

PostgreSQL’s community pronounces PostgreSQL as /ˈpoʊstɡrɛs ˌkjuː ˈɛl/.

### History of PostgreSQL

The PostgreSQL project started in 1986 at Berkeley Computer Science Department, University of California.

The project was originally named POSTGRES, about the older Ingres database which was also developed at Berkeley. The goal of the POSTGRES project was to add the minimal features needed to support multiple data types.

In 1996, the POSTGRES project was renamed to PostgreSQL to clearly illustrate its support for SQL. Today, PostgreSQL is commonly abbreviated as Postgres.

Since then, the PostgreSQL Global Development Group, a dedicated community of contributors continues to make the releases of the open-source and free database project.

Originally, PostgreSQL was designed to run on UNIX-like platforms. And then, PostgreSQL evolved to run on various platforms such as Windows, macOS, and Solaris.

### Common Use Cases of PostgreSQL

1. A robust database in the LAPP stack: LAPP stands for Linux, Apache, PostgreSQL, and PHP (or Python and Perl). PostgreSQL is primarily used as a robust back-end database that powers many dynamic websites and web applications.
2. General-purpose transaction database: Large corporations and startups alike use PostgreSQL as the primary database to support their applications and products.
3. Geospatial database: PostgreSQL with the PostGIS extension supports geospatial databases for geographic information systems (GIS).

### Language support

PostgreSQL supports the most popular programming languages:

* Python
* Java
* C#
* C/C++
* Ruby
* JavaScript (Node.js)
* Perl
* Go
* Tcl

### PostgreSQL feature highlights

PostgreSQL has many advanced features that other enterprise-class database management systems offer, such as:

* User-defined types
* Table inheritance
* Sophisticated locking mechanism
* Foreign key referential integrity
* Views, rules, subquery
* Nested transactions (savepoints)
* Multi-version concurrency control (MVCC)
* Asynchronous replication

The recent versions of PostgreSQL support the following features:

* Native Microsoft Windows Server version
* Tablespaces
* Point-in-time recovery

And more new features are added in each new release.

PostgreSQL is designed to be extensible. PostgreSQL allows you to define your data types, index types, functional languages, and so on.

If you don’t like any part of the system, you can always develop a custom plugin to enhance it to meet your requirements such as adding a new optimizer.