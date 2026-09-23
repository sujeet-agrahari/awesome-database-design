# Awesome Database Design [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated collection of resources, tutorials, tools, and best practices for designing efficient and scalable databases.

## Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
  - [Fundamentals](#fundamentals)
  - [Database Design Process](#database-design-process)
- [Core Concepts](#core-concepts)
  - [Naming Conventions](#naming-conventions)
  - [Normalization](#normalization)
  - [Entity-Relationship Modeling](#entity-relationship-modeling)
  - [Keys and Relationships](#keys-and-relationships)
- [Design Patterns](#design-patterns)
  - [Inheritance in Databases](#inheritance-in-databases)
  - [Subtype/Supertype Pattern](#subtypesupertype-pattern)
  - [Hierarchical Data Modeling](#hierarchical-data-modeling)
  - [Multi-language Database Design](#multi-language-database-design)
- [Performance & Optimization](#performance--optimization)
  - [Database Indexes](#database-indexes)
  - [Views and Materialized Views](#views-and-materialized-views)
  - [Query Optimization](#query-optimization)
- [Scalability](#scalability)
  - [Database Sharding](#database-sharding)
  - [Database Partitioning](#database-partitioning)
  - [Replication Strategies](#replication-strategies)
- [SQL & Query Languages](#sql--query-languages)
  - [SQL Tutorials](#sql-tutorials)
  - [Advanced SQL Concepts](#advanced-sql-concepts)
  - [SQL Best Practices](#sql-best-practices)
- [Database-Specific Resources](#database-specific-resources)
  - [PostgreSQL](#postgresql)
  - [MySQL](#mysql)
  - [MongoDB](#mongodb)
  - [Other Databases](#other-databases)
- [Learning Resources](#learning-resources)
  - [Courses & Video Tutorials](#courses--video-tutorials)
  - [Books](#books)
  - [Interactive Learning](#interactive-learning)
  - [Blogs & Articles](#blogs--articles)
- [Tools & Software](#tools--software)
  - [Database Design Tools](#database-design-tools)
  - [Migration Tools](#migration-tools)
  - [Monitoring & Profiling](#monitoring--profiling)
- [Best Practices](#best-practices)
  - [Common Pitfalls](#common-pitfalls)
  - [Security Considerations](#security-considerations)
  - [Data Integrity](#data-integrity)
- [Reference Materials](#reference-materials)
  - [Cheatsheets](#cheatsheets)
  - [Sample Schemas](#sample-schemas)
- [Community](#community)
- [Contributing](#contributing)

## Introduction

Being a self-taught programmer can be both challenging and rewarding. But when it comes to database design, finding the right resources and information can be difficult and time-consuming. This curated list aims to help developers at all levels master database design principles, from basic concepts to advanced patterns.

Over time, this collection has grown to include bookmarks, posts, courses, and links related to database design and entity modeling. Whether you're designing your first database or architecting a complex distributed system, you'll find valuable resources here.

## Getting Started

### Fundamentals

- [Database Design Basics](https://www.lucidchart.com/pages/database-diagram/database-design) - Introduction to database design concepts
- [What is a Database?](https://www.oracle.com/database/what-is-database/) - Oracle's comprehensive guide
- [Relational Database Concepts](https://www.geeksforgeeks.org/relational-model-in-dbms/) - Understanding the relational model
- [ACID Properties Explained](https://www.databricks.com/glossary/acid-transactions) - Transaction properties every developer should know
- [CAP Theorem](https://www.ibm.com/topics/cap-theorem) - Understanding distributed database tradeoffs
- [Database Types Comparison](https://www.prisma.io/dataguide/intro/comparing-database-types) - SQL vs NoSQL and when to use each

### Database Design Process

- [Database Conceptual Design | Entities and Relationships](https://www.youtube.com/watch?v=r0S5QqX1XpU) - Understanding conceptual design
- [Conceptual, Logical and Physical Design](https://www.youtube.com/watch?v=RzbH-oumqpo) - The three phases of database design
- [A Quick-Start Tutorial on Relational Database Design](https://www3.ntu.edu.sg/home/ehchua/programming/sql/Relational_Database_Design.html) - Comprehensive tutorial
- [Database Design Process](https://www.guru99.com/database-design.html) - Step-by-step guide
- [Data Modeling 101](https://www.agiledata.org/essays/dataModeling101.html) - Introduction to data modeling

## Core Concepts

### Naming Conventions

- [Database, Table and Column Naming Conventions](https://stackoverflow.com/questions/7662/database-table-and-column-naming-conventions) - Best practices discussion
- [Character Set and Collation](https://stackoverflow.com/questions/341273/what-does-character-set-and-collation-mean-exactly) - Understanding encoding
- [Choose Your Database Identifiers Wisely](https://racum.blog/articles/identifiers/) - Practical naming advice
- [SQL Naming Conventions](https://www.sqlshack.com/learn-sql-naming-conventions/) - Comprehensive naming guide
- [Database Naming Standards](https://www.c-sharpcorner.com/UploadFile/f0b2ed/what-is-naming-convention/) - Industry standards

### Normalization

- [Normalization - 1NF, 2NF, 3NF and 4NF](https://www.youtube.com/watch?v=UrYLYV7WSHM) - Video tutorial on normal forms
- [Database Normalization Explained](https://www.essentialsql.com/get-ready-to-learn-sql-database-normalization-explained-in-simple-english/) - Simple explanation
- [Difference between 1NF, 2NF, and 3NF](https://www.quora.com/What-is-the-difference-between-NF-2NF-and-3NF) - Clear comparison
- [The Difference between 2NF and 3NF](https://arctype.com/blog/2nf-3nf-normalization-example) - With examples
- [Database Normalization Tutorial](http://dotnetanalysis.blogspot.com/2012/01/database-normalization-sql-server.html) - Practical examples
- [When to Denormalize](https://www.red-gate.com/simple-talk/databases/sql-server/learn/denormalization-for-performance/) - Understanding tradeoffs
- [Normalization vs Denormalization](https://www.geeksforgeeks.org/denormalization-in-databases/) - When to use each approach

### Entity-Relationship Modeling

- [Entity-Relationship Diagrams](https://www.lucidchart.com/pages/er-diagrams) - Complete guide to ER diagrams
- [Data Modeling - Complex Relationships](https://www.youtube.com/watch?v=ZTPAMJ9MzdY) - Advanced relationship patterns
- [ER Model Tutorial](https://www.guru99.com/er-modeling.html) - Step-by-step ER modeling
- [Cardinality in Data Modeling](https://vertabelo.com/blog/cardinality-in-data-modeling/) - Understanding relationships
- [Crow's Foot Notation](https://www.vertabelo.com/blog/crow-s-foot-notation/) - Popular ER diagram notation

### Keys and Relationships

- [Primary Keys, Foreign Keys, and Relationships](https://www.essentialsql.com/what-is-the-difference-between-a-primary-key-and-a-foreign-key/) - Understanding keys
- [Identifying vs Non-identifying Relationships](https://stackoverflow.com/questions/762937/whats-the-difference-between-identifying-and-non-identifying-relationships) - Key differences
- [Composite Keys](https://www.geeksforgeeks.org/composite-key-in-sql/) - When and how to use them
- [Natural vs Surrogate Keys](https://www.vertabelo.com/blog/natural-key-vs-surrogate-key/) - Choosing the right key type
- [UUID vs Auto-increment](https://www.clever-cloud.com/blog/engineering/2015/05/20/why-auto-increment-is-a-terrible-idea/) - Primary key strategies

## Design Patterns

### Inheritance in Databases

- [Represent Inheritance in a Database](https://stackoverflow.com/questions/3579079/how-can-you-represent-inheritance-in-a-database) - Different approaches
- [Inheritance Modeling Strategies](https://stackoverflow.com/questions/190296/how-do-you-effectively-model-inheritance-in-a-database) - Detailed discussion
- [Table Inheritance Patterns](https://stackoverflow.com/questions/554522/something-like-inheritance-in-database-design) - Implementation patterns
- [Single Table Inheritance](https://sujeet-agrahari.hashnode.dev/sequelizejs-single-table-inheritance#heading-approach-iii) - Using Sequelize.js
- [Class Table Inheritance](https://www.martinfowler.com/eaaCatalog/classTableInheritance.html) - Martin Fowler's pattern
- [Concrete Table Inheritance](https://www.martinfowler.com/eaaCatalog/concreteTableInheritance.html) - Alternative approach

### Subtype/Supertype Pattern

- [Supertype/Subtype Design Pattern I](https://dba.stackexchange.com/questions/140604/implementing-subtype-of-a-subtype-in-type-subtype-design-pattern-with-mutually-e) - Implementation details
- [Supertype/Subtype Design Pattern II](https://dba.stackexchange.com/questions/149904/how-to-model-an-entity-type-that-can-have-different-sets-of-attributes) - Modeling different attributes
- [Polymorphic Associations](https://stackoverflow.com/questions/922184/why-can-you-not-have-a-foreign-key-in-a-polymorphic-association) - Understanding the pattern

### Hierarchical Data Modeling

- [Models for Hierarchical Data in SQL](https://www.youtube.com/watch?v=wuH5OoPC3hA) - Video overview
- [Storing Hierarchical Data](https://stackoverflow.com/questions/4048151/what-are-the-options-for-storing-hierarchical-data-in-a-relational-database) - Different approaches
- [Managing Hierarchical Data in MySQL](http://mikehillyer.com/articles/managing-hierarchical-data-in-mysql/) - Practical guide
- [Managing Hierarchical RDBMS](http://troels.arvin.dk/db/rdbms/links/#hierarchical) - Comprehensive resource
- [Nested Set Model](https://www.sitepoint.com/hierarchical-data-database/) - Popular hierarchical pattern
- [Closure Table Pattern](https://www.slideshare.net/billkarwin/models-for-hierarchical-data) - Efficient hierarchy storage
- [Materialized Path](https://www.postgresql.org/docs/current/ltree.html) - PostgreSQL ltree extension

### Multi-language Database Design

- [Best Practices for Multi-language Database Design](https://stackoverflow.com/questions/929410/what-are-best-practices-for-multi-language-database-design) - Comprehensive discussion
- [Multilingual Database Design in MySQL](https://www.apphp.com/tutorials/index.php?page=multilanguage-database-design-in-mysql) - Implementation guide
- [Internationalization Database Patterns](https://www.vertabelo.com/blog/data-model-for-a-multilingual-website/) - i18n patterns
- [Translation Table Pattern](https://stackoverflow.com/questions/316780/schema-for-a-multilanguage-database) - Common approach

## Performance & Optimization

### Database Indexes

- [How Do Database Indexes Work?](https://planetscale.com/blog/how-do-database-indexes-work) - Comprehensive explanation
- [Use The Index, Luke!](https://use-the-index-luke.com/) - Complete guide to database performance
- [B-Trees and B+ Trees](https://www.youtube.com/watch?v=aZjYr87r1b8) - Understanding index structures
- [MySQL: Building the Best INDEX](http://mysql.rjweb.org/doc.php/index_cookbook_mysql#many_to_many_mapping_table) - MySQL-specific guide
- [PostgreSQL Indexing: How, Why, and When?](https://www.youtube.com/watch?v=clrtT_4WBAw) - PostgreSQL indexing
- [Index Types Explained](https://www.postgresql.org/docs/current/indexes-types.html) - Different index types
- [Covering Indexes](https://www.brentozar.com/archive/2013/09/what-is-a-covering-index/) - Advanced indexing technique
- [Partial Indexes](https://www.postgresql.org/docs/current/indexes-partial.html) - Conditional indexes
- [Full-Text Search Indexes](https://www.postgresql.org/docs/current/textsearch-indexes.html) - Text search optimization

### Views and Materialized Views

- [Why Create a View in a Database?](https://stackoverflow.com/questions/1278521/why-do-you-create-a-view-in-a-database) - Understanding views
- [What are Materialized Views?](https://stackoverflow.com/questions/4463354/what-are-materialized-views) - Materialized views explained
- [Materialized Views vs Tables](https://www.postgresql.org/docs/current/rules-materializedviews.html) - When to use each
- [Indexed Views in SQL Server](https://www.sqlshack.com/sql-server-indexed-views/) - SQL Server perspective

### Query Optimization

- [SQL Query Optimization Techniques](https://www.sqlshack.com/query-optimization-techniques-in-sql-server-tips-and-tricks/) - Practical tips
- [Explain Plan Analysis](https://www.postgresql.org/docs/current/using-explain.html) - Understanding query plans
- [Query Performance Tuning](https://www.red-gate.com/simple-talk/databases/sql-server/performance-sql-server/sql-server-query-performance-tuning/) - Comprehensive guide
- [N+1 Query Problem](https://stackoverflow.com/questions/97197/what-is-the-n1-selects-problem-in-orm-object-relational-mapping) - Common pitfall

## Scalability

### Database Sharding

- [Database Sharding Crash Course](https://www.youtube.com/watch?v=d1fXBLqnFvc&t) - Video tutorial with Postgres examples
- [Sharding Pattern](https://docs.microsoft.com/en-us/azure/architecture/patterns/sharding) - Microsoft's guide
- [When to Shard Your Database](https://www.digitalocean.com/community/tutorials/understanding-database-sharding) - Decision guide
- [Consistent Hashing](https://www.toptal.com/big-data/consistent-hashing) - Sharding strategy
- [Vitess: Sharding for MySQL](https://vitess.io/) - MySQL sharding solution

### Database Partitioning

- [Database Partitioning Guide](https://github.com/sujeet-agrahari/postgres-db-partitioning-guide) - PostgreSQL partitioning
- [Table Partitioning Strategies](https://www.postgresql.org/docs/current/ddl-partitioning.html) - PostgreSQL docs
- [Partitioning vs Sharding](https://stackoverflow.com/questions/20771435/database-sharding-vs-partitioning) - Understanding the difference
- [Range vs Hash Partitioning](https://www.oracle.com/technical-resources/articles/database/sql-11g-partitioning.html) - Partitioning methods

### Replication Strategies

- [Database Replication Explained](https://www.mongodb.com/basics/replication) - Replication basics
- [Master-Slave vs Master-Master](https://www.digitalocean.com/community/tutorials/understanding-sql-and-nosql-databases-and-different-database-models) - Replication topologies
- [PostgreSQL Streaming Replication](https://www.postgresql.org/docs/current/warm-standby.html) - PostgreSQL replication
- [MySQL Replication](https://dev.mysql.com/doc/refman/8.0/en/replication.html) - MySQL replication guide

## SQL & Query Languages

### SQL Tutorials

- [SQLBolt - Interactive SQL Lessons](https://sqlbolt.com/) - Learn by doing
- [SQL Zoo - Tutorial and Exercises](https://sqlzoo.net/) - Practice SQL queries
- [Learn SQL - Scaler Topics](https://www.scaler.com/topics/sql/) - Comprehensive SQL guide
- [SQL Tutorial - W3Schools](https://www.w3schools.com/sql/) - Beginner-friendly tutorial
- [Mode SQL Tutorial](https://mode.com/sql-tutorial/) - Analytics-focused SQL
- [PostgreSQL Tutorial](https://www.postgresqltutorial.com/) - PostgreSQL-specific

### Advanced SQL Concepts

- [Subquery in SQL | Correlated Subquery](https://www.youtube.com/watch?v=nJIEIzF7tDw) - Advanced queries
- [SQL JOINS - Part 1](https://www.youtube.com/watch?v=0OQJDd3QqQM) - Understanding joins
- [SQL JOINS - Part 2](https://www.youtube.com/watch?v=RehbnzKHS28) - Advanced join techniques
- [Window Functions](https://www.postgresql.org/docs/current/tutorial-window.html) - Powerful analytical queries
- [Common Table Expressions (CTEs)](https://www.essentialsql.com/introduction-common-table-expressions-ctes/) - Recursive and non-recursive CTEs
- [Pivot and Unpivot](https://www.sqlshack.com/multiple-options-to-transposing-rows-into-columns/) - Data transformation
- [JSON in SQL](https://www.postgresql.org/docs/current/functions-json.html) - Working with JSON data

### SQL Best Practices

- [SQL Style Guide](https://www.sqlstyle.guide/) - Writing readable SQL
- [SQL Anti-patterns](https://pragprog.com/titles/bksqla/sql-antipatterns/) - Common mistakes to avoid
- [Parameterized Queries](https://cheatsheetseries.owasp.org/cheatsheets/Query_Parameterization_Cheat_Sheet.html) - Preventing SQL injection
- [Transaction Best Practices](https://www.red-gate.com/simple-talk/databases/sql-server/t-sql-programming-sql-server/sql-server-transactions-and-error-handling/) - Managing transactions

## Database-Specific Resources

### PostgreSQL

- [PostgreSQL Documentation](https://www.postgresql.org/docs/) - Official docs
- [Understanding Vacuuming in PostgreSQL](https://sujeet-agrahari.hashnode.dev/mastering-postgresql-vacuuming) - Maintenance guide
- [PostgreSQL Performance Tuning](https://wiki.postgresql.org/wiki/Performance_Optimization) - Optimization guide
- [Proper Use of Arrays in PostgreSQL](https://stackoverflow.com/questions/4389932/what-are-the-proper-use-cases-for-the-postgresql-array-datatype) - Array data type
- [PostgreSQL Exercises](https://pgexercises.com/) - Interactive learning
- [Awesome PostgreSQL](https://github.com/dhamaniasad/awesome-postgres) - Curated PostgreSQL resources

### MySQL

- [MySQL Documentation](https://dev.mysql.com/doc/) - Official docs
- [MySQL Performance Blog](https://www.percona.com/blog/) - Performance insights
- [MySQL Workbench Tutorial](https://dev.mysql.com/doc/workbench/en/) - Using MySQL Workbench
- [MySQL Indexing Best Practices](https://dev.mysql.com/doc/refman/8.0/en/optimization-indexes.html) - Index optimization
- [Awesome MySQL](https://github.com/shlomi-noach/awesome-mysql) - Curated MySQL resources

### MongoDB

- [MongoDB University](https://university.mongodb.com/) - Free courses
- [MongoDB Schema Design](https://www.mongodb.com/blog/post/6-rules-of-thumb-for-mongodb-schema-design) - NoSQL design patterns
- [MongoDB Data Modeling](https://docs.mongodb.com/manual/core/data-modeling-introduction/) - Official guide
- [Awesome MongoDB](https://github.com/ramnes/awesome-mongodb) - Curated MongoDB resources

### Other Databases

- [Redis Documentation](https://redis.io/documentation) - In-memory database
- [Cassandra Data Modeling](https://cassandra.apache.org/doc/latest/cassandra/data_modeling/index.html) - Wide-column store
- [DynamoDB Best Practices](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/best-practices.html) - AWS NoSQL
- [Neo4j Graph Database](https://neo4j.com/developer/graph-database/) - Graph database concepts

## Learning Resources

### Courses & Video Tutorials

- [Database Lessons Playlist](https://www.youtube.com/playlist?list=PL1LIXLIF50uXWJ9alDSXClzNCMynac38g) - Comprehensive video series
- [Introduction to RDBMS and Design](https://www.youtube.com/watch?v=Jk0r7vbzzL0&list=PL7NE8oKPrqN4hlEczr_aGWgeCHO--6UNJ) - Video course
- [Database Design Playlist](https://www.youtube.com/playlist?list=PLMi3udI_wFMWpfLPMvSnApwf4xr2a-sJ5) - Design tutorials
- [Carnegie Mellon Database Systems](https://www.youtube.com/playlist?list=PLSE8ODhjZXjbohkNBWQs_otTrBTrjyohi) - University lectures
- [Stanford Database Courses](https://online.stanford.edu/courses/soe-ydatabases-databases) - Stanford online courses
- [SQL Training Videos](http://www.metamanager.com/cbt) - SQL-focused training
- [freeCodeCamp Database Courses](https://www.freecodecamp.org/learn/relational-database/) - Free certification courses
- [Udacity Database Courses](https://www.udacity.com/course/intro-to-relational-databases--ud197) - Intro to databases

### Books

- [Database Design for Mere Mortals](https://www.amazon.com/Database-Design-Mere-Mortals-Hands/dp/0321884493) - Beginner-friendly book
- [SQL Antipatterns](https://pragprog.com/titles/bksqla/sql-antipatterns/) - Avoiding common mistakes
- [Designing Data-Intensive Applications](https://dataintensive.net/) - Modern database systems
- [Database Internals](https://www.databass.dev/) - How databases work internally
- [The Art of PostgreSQL](https://theartofpostgresql.com/) - PostgreSQL mastery
- [High Performance MySQL](https://www.oreilly.com/library/view/high-performance-mysql/9781492080503/) - MySQL optimization

### Interactive Learning

- [SQLBolt](https://sqlbolt.com/) - Interactive SQL lessons
- [SQL Zoo](https://sqlzoo.net/) - SQL exercises
- [PostgreSQL Exercises](https://pgexercises.com/) - PostgreSQL practice
- [LeetCode Database Problems](https://leetcode.com/problemset/database/) - SQL coding challenges
- [HackerRank SQL](https://www.hackerrank.com/domains/sql) - SQL practice problems
- [SQLPad](https://sqlpad.io/) - Online SQL editor

### Blogs & Articles

- [Things You Should Know About Databases](https://architecturenotes.co/things-you-should-know-about-databases/) - Essential knowledge
- [Database Journal](https://www.databasejournal.com/) - Featured articles
- [Percona Database Performance Blog](https://www.percona.com/blog/) - Performance insights
- [Planet PostgreSQL](https://planet.postgresql.org/) - PostgreSQL community blogs
- [MySQL Server Blog](https://mysqlserverteam.com/) - Official MySQL blog
- [High Scalability](http://highscalability.com/) - Scalability case studies
- [Database Trends and Applications](https://www.dbta.com/) - Industry news

## Tools & Software

### Database Design Tools

- [dbdiagram.io](https://dbdiagram.io/) - Draw ER diagrams painlessly
- [DrawDB](https://github.com/drawdb-io/drawdb) - Free, simple database design tool
- [DB Designer](https://www.dbdesigner.net/) - Online database designer
- [MySQL Workbench](https://www.mysql.com/products/workbench/) - MySQL official tool
- [pgModeler](https://www.pgmodeler.io/) - PostgreSQL database modeler
- [DBeaver](https://dbeaver.io/) - Universal database tool
- [DataGrip](https://www.jetbrains.com/datagrip/) - JetBrains database IDE
- [SQL Studio](https://sql-studio.frectonz.et) - Modern SQL editor
- [Luna Modeler](https://www.datensen.com) - Multi-platform database modeler
- [Oracle SQL Developer Data Modeler](https://www.oracle.com/in/database/sqldeveloper/technologies/sql-data-modeler/) - Oracle's modeling tool
- [dbForge Studio](https://www.devart.com/dbforge/mysql/studio/database-designer.html) - MySQL design tool
- [Valentina Studio](https://valentina-db.com/en/valentina-studio-13) - Multi-database tool
- [Dia Diagram Editor](http://dia-installer.de/) - Open-source diagram tool
- [ArchiMate Tool](https://www.archimatetool.com/) - Enterprise architecture modeling
- [Vertabelo](https://www.vertabelo.com/) - Online database modeler
- [QuickDBD](https://www.quickdatabasediagrams.com/) - Quick database diagrams

### Migration Tools

- [Flyway](https://flywaydb.org/) - Database migration tool
- [Liquibase](https://www.liquibase.org/) - Database schema change management
- [Alembic](https://alembic.sqlalchemy.org/) - Python database migrations
- [Prisma Migrate](https://www.prisma.io/migrate) - Modern migration tool
- [Sqitch](https://sqitch.org/) - Database change management
- [Bytebase](https://www.bytebase.com/) - Database governance platform: UI-driven or GitOps workflow (versioned or declarative), SQL review, approval, and a full API

### Monitoring & Profiling

- [pgAdmin](https://www.pgadmin.org/) - PostgreSQL administration
- [MySQL Enterprise Monitor](https://www.mysql.com/products/enterprise/monitor.html) - MySQL monitoring
- [Datadog Database Monitoring](https://www.datadoghq.com/product/database-monitoring/) - Multi-database monitoring
- [New Relic Database Monitoring](https://newrelic.com/platform/database-monitoring) - Performance monitoring
- [pg_stat_statements](https://www.postgresql.org/docs/current/pgstatstatements.html) - PostgreSQL query statistics
- [Percona Monitoring and Management](https://www.percona.com/software/database-tools/percona-monitoring-and-management) - Open-source monitoring

## Best Practices

### Common Pitfalls

- [Using NULL Properly](https://dba.stackexchange.com/questions/5222/why-shouldnt-we-allow-nulls) - NULL handling debate
- [8 Reasons Why MySQL's ENUM Is Evil](http://komlenic.com/244/8-reasons-why-mysqls-enum-data-type-is-evil/) - ENUM pitfalls
- [Database Design Mistakes](https://www.red-gate.com/simple-talk/databases/sql-server/database-administration-sql-server/ten-common-database-design-mistakes/) - Common errors
- [ORM Anti-patterns](https://stackoverflow.com/questions/1279613/what-is-an-orm-how-does-it-work-and-how-should-i-use-one) - ORM best practices
- [Boolean Field Naming](https://stackoverflow.com/questions/3492322/naming-convention-for-boolean-fields) - Naming conventions

### Security Considerations

- [SQL Injection Prevention](https://cheatsheetseries.owasp.org/cheatsheets/SQL_Injection_Prevention_Cheat_Sheet.html) - OWASP guide
- [Database Security Best Practices](https://www.oracle.com/security/database-security/best-practices.html) - Comprehensive security guide
- [Encryption at Rest](https://www.postgresql.org/docs/current/encryption-options.html) - Data encryption
- [Row Level Security](https://www.postgresql.org/docs/current/ddl-rowsecurity.html) - Fine-grained access control
- [Database Audit Logging](https://www.postgresql.org/docs/current/pgaudit.html) - Tracking database changes
- [RowShield](https://rowshield.dev) - Probes a deployed Supabase app for reachable and exposed data, then monitors connected projects for RLS and schema drift.

### Data Integrity

- [Referential Integrity](https://www.essentialsql.com/what-is-referential-integrity/) - Maintaining relationships
- [Check Constraints](https://www.postgresql.org/docs/current/ddl-constraints.html) - Data validation
- [Triggers for Data Integrity](https://www.postgresql.org/docs/current/trigger-definition.html) - Automated validation
- [Soft Delete Pattern](https://stackoverflow.com/questions/2549839/are-soft-deletes-a-good-idea) - Logical deletion
- [Temporal Tables](https://www.postgresql.org/docs/current/ddl-system-columns.html) - Historical data tracking

## Reference Materials

### Cheatsheets

- [SQL Commands Cheatsheet](https://drive.google.com/file/d/1E0f4PC75wNCXxKHXxmx0Jq30BNUc1rKf/view?usp=sharing) - Quick reference
- [PostgreSQL Cheatsheet](https://postgrescheatsheet.com/) - PostgreSQL commands
- [MySQL Cheatsheet](https://devhints.io/mysql) - MySQL quick reference
- [SQL Join Visualizer](https://sql-joins.leopard.in.ua/) - Visual join guide
- [Database Normalization Cheatsheet](https://www.databasestar.com/database-normalization/) - Normal forms reference

### Sample Schemas

- [Premade Database Designs and Models](http://www.databaseanswers.org/data_models/) - Real-world examples
- [PostgreSQL Sample Databases](https://www.postgresqltutorial.com/postgresql-getting-started/postgresql-sample-database/) - Practice databases
- [MySQL Sample Databases](https://dev.mysql.com/doc/index-other.html) - Example schemas
- [Northwind Database](https://github.com/pthom/northwind_psql) - Classic sample database
- [Sakila Database](https://dev.mysql.com/doc/sakila/en/) - DVD rental schema

## Community

- [Database Administrators Stack Exchange](https://dba.stackexchange.com/) - Q&A community
- [r/Database](https://www.reddit.com/r/Database/) - Reddit community
- [r/SQL](https://www.reddit.com/r/SQL/) - SQL discussions
- [PostgreSQL Slack](https://postgres-slack.herokuapp.com/) - PostgreSQL community
- [MySQL Forums](https://forums.mysql.com/) - MySQL community
- [Database Weekly Newsletter](https://dbweekly.com/) - Weekly database news

## Contributing

Are you passionate about database design? 🤔 Do you have some great resources or topics to share? We'd love to hear from you! 💡 Please feel free to contribute to the repository and don't forget to raise a PR or suggest any improvements. 🙌 Thank you for your support!

### How to Contribute

1. **Fork** the repository to your GitHub account
2. **Clone** your fork to your local machine:
   ```bash
   git clone https://github.com/your-username/awesome-database-design.git
   ```
3. **Create a branch** for your changes:
   ```bash
   git checkout -b add-new-resources
   ```
4. **Make your changes** to the `README.md` file:
   - Add new links with clear descriptions
   - Ensure links are working and relevant
   - Place resources in the appropriate category
   - Follow the existing formatting style
5. **Commit your changes** with a clear message:
   ```bash
   git commit -m "Add resources for query optimization"
   ```
6. **Push** to your fork:
   ```bash
   git push origin add-new-resources
   ```
7. **Create a Pull Request** from your fork to the main repository
8. **Wait for review** and respond to any feedback

### Contribution Guidelines

- Ensure links are high-quality and relevant to database design
- Provide clear, concise descriptions for each resource
- Check that links are not already in the list
- Verify that all links are working before submitting
- Use proper markdown formatting
- Keep descriptions objective and informative
- For paid resources, clearly indicate if they require payment

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=sujeet-agrahari/awesome-database-design&type=Date)](https://star-history.com/#sujeet-agrahari/awesome-database-design&Date)

---

**[⬆ Back to Top](#contents)**

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
