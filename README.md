[![Quarto Publish](https://github.com/vanHeemstraSystems/map-management/actions/workflows/publish.yml/badge.svg)](https://github.com/vanHeemstraSystems/map-management/actions/workflows/publish.yml)

permission-management
# Permission Management

Can be read as "Permission Management" at https://app.gitbook.com/s/Rs3XPuVclvoj92Exb9AA/

Can be browsed as "Permission Management" at https://vanheemstrasystems.github.io/permission-management/

Documentation of this repository is automatically done with Quarto using GitHub Actions as described at https://github.com/vanHeemstraSystems/quarto-to-github-pages/blob/main/300/300/README.md

Based on "How to Run PostgreSQL and pgAdmin Using Docker" at https://towardsdatascience.com/how-to-run-postgresql-and-pgadmin-using-docker-3a6a8ae918b5

Based on "Permit.io - Never Build Permissions Again" at https://www.permit.io/

Create yarn.lock file as follows:

```
$ cd containers/app/main
$ yarn install
```

Run as follows:

```
$ cd containers/app
$ docker-compose --file docker-compose.dev.yml --project-name permission-management-dev up --build -d
```
