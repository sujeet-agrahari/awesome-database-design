# Awesome Database Design [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A comprehensive guide to database design that includes resources, tutorials and tools to help you create an efficient database schema.

## Introduction

Being a self-taught programmer can be both challenging and rewarding. But when it comes to database design, finding the right resources and information can be difficult and time-consuming. This is why I've created this list - to help others who may be facing similar difficulties.

Over the past few months, I've accumulated a vast collection of bookmarks, posts, courses, and links related to database design and entity modeling. This list is my attempt to organize those resources and make them accessible to others who are interested in learning database design.

## How to use this list

This list is organized into categories for easy navigation. If you're looking for a specific topic, you can use the search function (`Ctrl + F` or `Cmd + F` on macOS) to quickly find what you're looking for.

## Topics:

- [Awesome Database Design ](#awesome-database-design-)
  - [Introduction](#introduction)
  - [How to use this list](#how-to-use-this-list)
  - [Topics:](#topics)
    - [Naming Convention](#naming-convention)
    - [Normalization](#normalization)
    - [Entity-relationship modeling](#entity-relationship-modeling)
    - [Conceptual database design](#conceptual-database-design)
    - [Hierarchical data modeling](#hierarchical-data-modeling)
    - [Logical database design](#logical-database-design)
    - [Views](#views)
    - [Database Indexes](#database-indexes)
    - [Inheritance in database design](#inheritance-in-database-design)
    - [Multi-language database design](#multi-language-database-design)
    - [Subtype/supertype design pattern](#subtypesupertype-design-pattern)
    - [Database Sharding](#database-sharding)
    - [Database Partition](#database-partition)
    - [SQL](#sql)
    - [Database Lessons](#database-lessons)
    - [Common Database Questions and Suggestions](#common-database-questions-and-suggestions)
    - [Cheatsheets](#cheatsheets)
    - [Database Design Tools](#database-design-tools)
  - [Star History](#star-history)
  - [Please contribute](#please-contribute)
    - [Follow these steps to contribute](#follow-these-steps-to-contribute)

### Naming Convention

- [Database, Table and Column Naming Conventions](https://stackoverflow.com/questions/7662/database-table-and-column-naming-conventions)
- [Character set and Collation](https://stackoverflow.com/questions/341273/what-does-character-set-and-collation-mean-exactly)

### Normalization

- [Normalization - 1NF, 2NF, 3NF and 4NF](https://www.youtube.com/watch?v=UrYLYV7WSHM)
- [Difference between NF, 2NF, and 3NF](https://www.quora.com/What-is-the-difference-between-NF-2NF-and-3NF)
- [Database Normalization Tutorial with example](http://dotnetanalysis.blogspot.com/2012/01/database-normalization-sql-server.html)
- [The Difference between 2NF and 3NF](https://arctype.com/blog/2nf-3nf-normalization-example)

### Entity-relationship modeling

- [Database Conceptual Design| Entities and Relationships](https://www.youtube.com/watch?v=r0S5QqX1XpU)
- [Data Modeling - Complex Relationships](https://www.youtube.com/watch?v=ZTPAMJ9MzdY)
- [A Quick-Start Tutorial on Relational Database Design](https://www3.ntu.edu.sg/home/ehchua/programming/sql/Relational_Database_Design.html)

### Conceptual database design

- [Database Conceptual Design| Entities and Relationships](https://www.youtube.com/watch?v=r0S5QqX1XpU)
- [Database Conceptual Design](https://www.youtube.com/watch?v=ZTPAMJ9MzdY)
- [conceptual, logical and physical design for a database](https://www.youtube.com/watch?v=RzbH-oumqpo)

### Hierarchical data modeling

- [Models for Hierarchical Data in SQL](https://www.youtube.com/watch?v=wuH5OoPC3hA)
- [Storing hierarchical data in a relational database](https://stackoverflow.com/questions/4048151/what-are-the-options-for-storing-hierarchical-data-in-a-relational-database)
- [Managing hierarchical data in mysql](http://mikehillyer.com/articles/managing-hierarchical-data-in-mysql/)
- [Managing hierarchical RDBSM](http://troels.arvin.dk/db/rdbms/links/#hierarchical)

### Logical database design

- [Database Conceptual Design| Entities and Relationships](https://www.youtube.com/watch?v=r0S5QqX1XpU)
- [Data Modeling - Complex Relationships](https://www.youtube.com/watch?v=ZTPAMJ9MzdY)
- [conceptual, logical and physical design for a database](https://www.youtube.com/watch?v=RzbH-oumqpo)
- [Premade Database Designs and Models](http://www.databaseanswers.org/data_models/)

### Views

- [Why do you create a View in a database?](https://stackoverflow.com/questions/1278521/why-do-you-create-a-view-in-a-database)
- [What are materialized views?](https://stackoverflow.com/questions/4463354/what-are-materialized-views)

### Database Indexes

- [How do database indexes work?](https://planetscale.com/blog/how-do-database-indexes-work)
- [MySQL: Building the best INDEX for a given SELECT](http://mysql.rjweb.org/doc.php/index_cookbook_mysql#many_to_many_mapping_table)
- [B Trees and B+ Trees](https://www.youtube.com/watch?v=aZjYr87r1b8)
- [A guide to database performance for developers](https://use-the-index-luke.com/)
- [PostgreSQL Indexing : How, why, and when?](https://www.youtube.com/watch?v=clrtT_4WBAw)

### Inheritance in database design

- [Represent inheritance in a database](https://stackoverflow.com/questions/3579079/how-can-you-represent-inheritance-in-a-database)
- [Inheritance in a database I](https://stackoverflow.com/questions/190296/how-do-you-effectively-model-inheritance-in-a-database)
- [Inheritance in a database II](https://stackoverflow.com/questions/554522/something-like-inheritance-in-database-design)
- [Storing hierarchical data in a relational database](https://stackoverflow.com/questions/4048151/what-are-the-options-for-storing-hierarchical-data-in-a-relational-database)
- [Models for Hierarchical Data in SQL](https://www.youtube.com/watch?v=wuH5OoPC3hA)
- [Managing hierarchical data in mysql](http://mikehillyer.com/articles/managing-hierarchical-data-in-mysql/)
- [Single Table Inheritance Using Sequelize.js](https://sujeet-agrahari.hashnode.dev/sequelizejs-single-table-inheritance#heading-approach-iii)

### Multi-language database design

- [Database design for multiple language](https://stackoverflow.com/questions/929410/what-are-best-practices-for-multi-language-database-design)
- [Best practices for multi-language database design](https://stackoverflow.com/questions/929410/what-are-best-practices-for-multi-language-database-design)
- [Managing hierarchical RDBSM](http://troels.arvin.dk/db/rdbms/links/#hierarchical)
- [Multilingual Database Design in MySQL](https://www.apphp.com/tutorials/index.php?page=multilanguage-database-design-in-mysql)

### Subtype/supertype design pattern

- [Super type/Sub type design pattern I](https://dba.stackexchange.com/questions/140604/implementing-subtype-of-a-subtype-in-type-subtype-design-pattern-with-mutually-e)
- [Super type/Sub type design pattern II](https://dba.stackexchange.com/questions/149904/how-to-model-an-entity-type-that-can-have-different-sets-of-attributes)

### Database Sharding

- [Database Sharding Crash Course (with Postgres examples)](https://www.youtube.com/watch?v=d1fXBLqnFvc&t)

### Database Partition

- [Database Partitioning Guide](https://github.com/sujeet-agrahari/postgres-db-partitioning-guide)

### SQL

- [SQL Training Videos](http://www.metamanager.com/cbt)
- [Proper use of array in Postgresql](https://stac43912/what-are-the-proper-use-cases-for-the-postgresql-array-datatype)
- [Difference between identifying and non-identifying relationships](https://stackoverflow.com/questions/762937/whats-the-difference-between-identifying-and-non-identifying-relationships)

- [Subquery in SQL | Correlated Subquery ](https://www.youtube.com/watch?v=nJIEIzF7tDw)
- [Learn SQL in Detail](https://www.scaler.com/topics/sql/)
- [Interactive SQL Lessons](https://sqlbolt.com/)
- [SQL tutorial and exercises](https://sqlzoo.net/)
- [SQL JOINS - Part 1](https://www.youtube.com/watch?v=0OQJDd3QqQM)
- [SQL JOINS - Part 2](https://www.youtube.com/watch?v=RehbnzKHS28)

### Database Lessons

- [Database Lessons](https://www.youtube.com/playlist?list=PL1LIXLIF50uXWJ9alDSXClzNCMynac38g)

- [Introduction to RDBMS and design](https://www.youtube.com/watch?v=Jk0r7vbzzL0&list=PL7NE8oKPrqN4hlEczr_aGWgeCHO--6UNJ)

- [Database Design Playlist](https://www.youtube.com/playlist?list=PLMi3udI_wFMWpfLPMvSnApwf4xr2a-sJ5)
- [Carnegie Mellon University lectures](https://www.youtube.com/playlist?list=PLSE8ODhjZXjbohkNBWQs_otTrBTrjyohi)
- [Things You Should Know About Databases](https://architecturenotes.co/things-you-should-know-about-databases/)
- [Stanford Database Courses](https://online.stanford.edu/courses/soe-ydatabases-databases)
- [Database Journal - FEATURED DATABASE ARTICLES](https://www.databasejournal.com/)

### Common Database Questions and Suggestions

- [Using NULL properly- You decide ](https://dba.stackexchange.com/questions/5222/why-shouldnt-we-allow-nulls)
- [8 Reasons Why MySQL's ENUM Data Type Is Evil](http://komlenic.com/244/8-reasons-why-mysqls-enum-data-type-is-evil/)
- [Understanding Vacuuming in PostgreSQL](https://sujeet-agrahari.hashnode.dev/mastering-postgresql-vacuuming)

### Cheatsheets

- [SQL Commands](https://drive.google.com/file/d/1E0f4PC75wNCXxKHXxmx0Jq30BNUc1rKf/view?usp=sharing)

### Database Design Tools

- [Draw Entity-Relationship Diagrams, Painlessly](https://dbdiagram.io/)
- [DB DESIGNER](https://www.dbdesigner.net/)
- [ArchiMate models and sketches](https://www.archimatetool.com/)
- [PG Modeler](https://www.pgmodeler.io/)
- [Dia Diagram Editor](http://dia-installer.de/)
- [Data Modeling with Oracle SQL Developer](https://www.oracle.com/in/database/sqldeveloper/technologies/sql-data-modeler/)
- [MySQL Workbench](https://www.mysql.com/products/workbench/)
- [dbForge Studio for MySQL](https://www.devart.com/dbforge/mysql/studio/database-designer.html)
- [Valentina Studeio 13](https://valentina-db.com/en/valentina-studio-13?ref=producthunt)
- [Luna Modeler](https://www.datensen.com)
- [Draw DB: Free, simple database design tool](https://github.com/drawdb-io/drawdb)

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=sujeet-agrahari/awesome-database-design&type=Date)](https://star-history.com/#sujeet-agrahari/awesome-database-design&Date)

## Please contribute

Are you passionate about database design? 🤔 Do you have some great resources or topics to share? We'd love to hear from you! 💡 Please feel free to contribute to the repository and don't forget to raise a PR or suggest any improvements. 🙌 Thank you for your support!

### Follow these steps to contribute

1. Clone the repository to your local machine using the git clone command.
2. Make changes to the `README.md` file by editing it in your preferred text editor. You can add new links or suggest modifications to existing ones.
3. Commit your changes using the `git commit` command. Make sure to include a _clear and concise commit message_ that describes the changes you made.
4. Push your changes to the repository using the git push command.
5. Create a pull request by navigating to the original repository and clicking the "_New pull request_" button. GitHub will guide you through the process of creating a pull request.
6. Wait for the repository owner to review and merge your changes. Be sure to respond to any feedback or comments they provide.
7. If your changes are accepted, you can continue contributing to the repository by repeating the above steps for additional changes.
