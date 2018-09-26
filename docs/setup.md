Setup
=====

Configuration
-------------

Replace `.env` with your own preferred username and password for Postgres otherwise a default of postgres/postgres will be used for the username and password.

```
POSTGRES_USE=postgres
POSTGRES_PASSWORD=postgres
```

Build
-----

```bash
docker-compose build
```

Run
---

```bash
docker-compose up
```

Connect to Postgres
-------------------

```
psql postgres://postgres:example@0.0.0.0:5432
```

Connect to Adminer
------------------

http://localhost:8080

Shutdown
--------

```bash
docker-compose down
```
