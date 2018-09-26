PostgreSQL By Example
=====================

Hey there! This is PostgreSQL by Example! This tutorial is for you if you've got some programming experience and if you're not too familiar with Postgres (v9.6) or SQL. This tutorial progressively goes into more and more advanced topic so feel free to skip ahead.

If you prefer the soft touch of paper, the delicious smell of a real book, the possibility to physically hug a document, or just want to boast by padding your bookcase, you're out of luck as this is a paper free tutorial!

If you want to contact me, check out my twitter account, find me on #apoclyps.

So what's PostgreSQL
--------------------

---

> PostgreSQL is a general purpose and object-relational database management system, the most advanced open source database system. PostgreSQL was designed to run on UNIX-like platforms. However, PostgreSQL was then also designed to be portable so that it could run on various platforms such as Mac OS X, Solaris, and Windows. PostgreSQL is free and open source software. Its source code is available under PostgreSQL license, a liberal open source license. You are free to use, modify and distribute PostgreSQL in any form. PostgreSQL requires very minimum maintained efforts because of its stability. Therefore, if you develop applications based on PostgreSQL, the total cost of ownership is low in comparison with other database management systems.

Prerequisites
-------------

-	[Docker](https://www.docker.com/)
-	[psql](http://postgresguide.com/utilities/psql.html)

Tutorials
---------

-	[Setup](docs/setup.md)

Just want to start using it?
----------------------------

Running this command will start Postgres and Adminer in the background:

```sh
docker-compose up -d
```

Postgres will be available at `postgres://postgres:example@0.0.0.0:5432` and Adminer will be available at http://localhost:8080
