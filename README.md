# database-engineering-course

This repository contains the code samples from a great course 
"Fundamentals of Database Engineering" by Hussein Nasser.

It covers design, fundamental concepts, and an explanation of the database design.
It's the next step after learning SQL basics to become an aware and 
skilled backend engineer.

It can bring your database skills to the next level and let you design reliable and error-proof systems.

Set up details:
- database used: PostgreSQL run from the docker container

### Prerequisites:
- installed docker

To run postgres database in a container, use below command:
```
docker run --name pgmain -d -e POSTGRES_PASSWORD=postgres postgres
```

To enter the container:
```
docker exec -it pgmain bash
```

