# Tutorial for GraphQL

Credits to: https://github.com/alexisrolland/docker-postgresql-postgraphile

## Setup

1. `docker-compose build` to build the images
2. `docker-compose up -d` to run all containers in the background

| Container |  Docker |
| --- | --- |
| GraphQL API Documentation | https://localhost:5433/graphiql |
| GraphQL API | https://localhost:5433/graphql |
| PostgreSQL Database | host: localhost, port: 5432 |