# The "Database as Code" Manifesto

- Treat your database or other storage system as a code
- All changes and operations with database and all queries to database should be expressed as a plain old code
- Git (or anything else VCS) is a single source of truth for database code
- SQL actually is a main database language supported by almost all DBMS 
- SQL is not a bytecode for your data and your database, it's a normal human-oriented program language
- SQL is designed not only for data, but also for metadata
- Database code is not only DDL and other migration scripts, DML and all kinds of SQL scripts too
- Database code is a normal code and it also needs static analysys, code review (especialy by DBA, analysts and business people) , tests and automation of it all. 

### Resources:
- [Database as Code: a Novel Concept](https://dzone.com/articles/database-as-code-a-novel-concept)
- [SQL prevents database corruption and injection, except in the ridiculous movie’s hacker scenes.](https://medium.com/@FranckPachot/sql-prevents-database-corruption-and-injection-except-in-the-ridiculous-movies-hacker-scenes-8b89479468b4)
- [Visualizing SQL Plan Execution Time With FlameGraphs](https://blog.tanelpoder.com/posts/visualizing-sql-plan-execution-time-with-flamegraphs/)
