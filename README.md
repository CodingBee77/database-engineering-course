# database-engineering-course

This repository contains the code samples from a great course 
"Fundamentals of Database Engineering" by Hussein Nasser.

It covers design, fundamental concepts, and an explanation of the database design.
It's the next step after learning SQL basics to become an aware and 
skilled backend engineer.

It can bring your database skills to the next level and let you design reliable and error-proof systems.

Set up details:
- database used: PostgreSQL 14.1 run from the docker container

### Prerequisites:
- installed docker

To run postgres database with docker-compose file:
```
docker-compose -f docker-compose.yml up
```

To enter the database inside the container:

```
docker exec -it {container name} psql -U {username} -d {table name}
```


### Project description:

2 javascript scripts to automate partitioning for database with 1B rows.

"create_partitions.mjs" - create main customers table and partitions
"populate_customers.mjs" - populate data into previously defined partitions


