# Bounce AE challenge

## Setting up the project

### Pre requisites

- Docker and docker-compose installed
- [dbt](https://docs.getdbt.com/docs/installation) installed

### Steps

1. Clone the repository
2. Run `docker-compose up` to start the database
3. Run `dbt seed` to load the data into the database
4. Done. You can now run `dbt run` to run the models and `dbt test` to run the tests
