# Tutorial for GraphQL

Credits to: https://github.com/alexisrolland/docker-postgresql-postgraphile

## Setup

1. `docker-compose build` to build the images
2. `docker-compose up -d` to run all containers in the background

| Container             |  Docker                               |
| ---                   | ---                                   |
| GraphiQL              | https://localhost:5433/graphiql       |
| GraphQL               | https://localhost:5433/graphql        |
| PGAdmin               | https://localhost:5050                |
| PostgreSQL Database   | host: forum-example-db, port: 5432    |
