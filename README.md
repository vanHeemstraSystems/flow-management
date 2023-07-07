[![Quarto Publish](https://github.com/vanHeemstraSystems/flow-management/actions/workflows/publish.yml/badge.svg)](https://github.com/vanHeemstraSystems/flow-management/actions/workflows/publish.yml)

flow-management
# Flow Management

Can be read as "Flow Management" at https://app.gitbook.com/s/Rs3XPuVclvoj92Exb9AA/

Can be browsed as "Flow Management" at https://vanheemstrasystems.github.io/flow-management/

Documentation of this repository is automatically done with Quarto using GitHub Actions as described at https://github.com/vanHeemstraSystems/quarto-to-github-pages/blob/main/300/300/README.md

Based on "How to Run PostgreSQL and pgAdmin Using Docker" at https://towardsdatascience.com/how-to-run-postgresql-and-pgadmin-using-docker-3a6a8ae918b5

Based on "Sequential Workflow Designer" at [https://www.permit.io/](https://github.com/nocode-js/sequential-workflow-designer)

Create yarn.lock file as follows:

```
$ cd containers/app/main
$ yarn install
```

Run as follows:

```
$ cd containers/app
$ docker-compose --file docker-compose.dev.yml --project-name flow-management-dev up --build -d
```
