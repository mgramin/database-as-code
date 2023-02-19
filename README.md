# The "Database as Code" Manifesto

We believe that we can interact with our databases and storage (including queries, administration and the entire DB lifecycle) as if they were plain code. And we call it - "Database as Code" (such as "infrastructure as code", "configuration as code", "pipeline as code" and so on).

### Base principles:
- All changes and operations with the database and all queries (ideally) against the database should be expressed as a plain old code
- Git (or anything else VCS) is a single source of truth for database code
- SQL actually is a main database language supported by almost all DBMS 
- SQL is not a bytecode for your data and your database, it's a normal human-oriented program language ([why](https://gramin.pro/posts/sql-is-not-a-bytecode-for-data))
- SQL is designed not only for data, but also for metadata
- Database code is not only DDL and other migration scripts, DML and all kinds of SQL scripts too
- Database code is a normal code, and it also needs static analysis, code review (especially by DBA, analysts and business people) , tests and automation of it all
- DBAs and data people should be integrated with Dev and Ops
- Ability to release on demand.

### Resources:
- [Database as Code: a Novel Concept](https://dzone.com/articles/database-as-code-a-novel-concept)
- [Database as Code - the Good, the Bad and the Ugly](https://bytebase.com/blog/database-as-code)
- [The Database Inside Your Codebase](https://feifan.blog/posts/the-database-inside-your-codebase)
- [Database as Code. Not only migrations](https://gramin.pro/posts/database-as-code)

### Talks:
- Aren't we forgetting someone? ([slides](https://speakerdeck.com/tastapod/arent-we-forgetting-someone))
- Database as Code. Not only migrations ([video](https://youtu.be/_XgLLJQ5pZw), [slides](https://github.com/mgramin/percona-community-live-2022))

### Tools:
- [Liquibase](https://www.liquibase.org) - database schema change management solution and [standard](https://twitter.com/pramodsadalage/status/1494398226253897733?t=_MKNMnmKBXUMDKJi-ZcYmg&s=19) realization of [Refactoring Databases](https://databaserefactoring.com) patterns.
- [dbt](https://github.com/dbt-labs/dbt-core) - enables data analysts and engineers to transform their data using the same practices that software engineers use to build applications.
- [Yesql](https://github.com/krisajenkins/yesql) - a Clojure library for using SQL. Keep the SQL as SQL.
- [HugSQL](https://www.hugsql.org) - a Clojure library for embracing SQL, creating a clean separation of Clojure and SQL code.
- [PugSQL](https://pugsql.org) - Python library inspired by HugSQL.
- [Malewicz](https://github.com/mgramin/malewicz) - Hackable GUI SQL-manager written in SQL itself.
- [Pigsty](https://github.com/Vonng/pigsty) - Describe database with code, then create them in one-click.
- [Bytebase](https://bytebase.com) - Safer and faster database change and version control for teams.
- [aiosql](https://github.com/nackjicholson/aiosql) - SQL is code. Write it, version control it, comment it, and run it using files.
- [Synthesized](https://www.synthesized.io) - Create high-quality data for machine learning, application development and testing with easy-to-use config files.
- [Evidence](https://github.com/evidence-dev/evidence) - Build a polished business intelligence system using only SQL and markdown.
- [Soda](https://www.soda.io) - Check Data As Code.
