# Docker PERN Template

The purpose of this repo is to provide a template so you can quickly get up and running with a PERN stack application.

## How To Use

Once you have started the Docker container using the provided tools and commands below you will need to navigate to [http://localhost:8000](http://localhost:8000).

### Dependancies

You will need to install:

- [Docker](https://docs.docker.com/get-docker/)
- [Node.JS / NPM](https://nodejs.org/en/download/)

### Controls

Starts Docker containers and networks (will build first if no build exists):

```
npm run docker:up
```

Builds Docker images from a docker-compose.yml, Dockerfile and "context";

```
npm run docker:build
```

Stops Docker containers and networks:

```
npm run docker:down
```

### Access to PgAdmin4

- **URL:** [http://localhost:8000](http://localhost:8000)
- **Username:** `pgadmin4@pgadmin.org`
- **Password:** `admin`

#### Add a new server in PgAdmin4

- **Host name/address** `db`
- **Port** `5432`
- **Username** `pern_db`
- **Password** `root`

## Technologies Used

- Docker
- PostgreSQL
- Express JS
- React
- Node JS

## Abbreviations Used

- PERN = (PostgreSQL, Express JS, React, Node.JS)
