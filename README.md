# Docker compose Postgresql & PgAdmin

## Requirements:

- docker
- docker-compose

## Quick Start

- `git clone git@github.com:lohazo/docker-compose-postgresql.git`
- Go inside of directory, `cd compose-postgres`
- Run this command `docker-compose up -d`

## Environments

This Compose file contains the following environment variables:

- `POSTGRES_USER` the default value is **postgres**
- `POSTGRES_PASSWORD` the default value is **postgres**
- `PGADMIN_PORT` the default value is **5555**
- `PGADMIN_DEFAULT_EMAIL` the default value is **pgadmin4@pgadmin.org**
- `PGADMIN_DEFAULT_PASSWORD` the default value is **admin**

## Access to postgres:

- `localhost:5432`
- **Username:** postgres (default)
- **Password:** postgres (default)

## Access to PgAdmin:

- **URL:** `http://localhost:5555`
- **Username:** pgadmin4@pgadmin.org (default)
- **Password:** admin (default)

## Add a new server in PgAdmin:

- **Host name/address** `postgres`
- **Port** `5432`
- **Username** as `POSTGRES_USER`, by default: `postgres`
- **Password** as `POSTGRES_PASSWORD`, by default `postgres`
