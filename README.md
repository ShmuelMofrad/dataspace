# dataspace

if you want to learn SQL without pain on the cloud, this dataspace is for you.
This is a Postgresql and VSCode development environment on the Docker.

## Tools

- install [docker-Ex](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)

run Terminal on **.devcontainer** directory
## Docker
 - Build

         docker build -t postgres .
 
 - Docker-compose
        
           docker-compose up -d

           docker-compose -f multiple-db-docker-compose.yml up -d
           
           docker-compose -f multiple-db-docker-compose.yml down


## Adminer

 - Database: **postgres**
   - user: postgres
   - pass: example
   - db: postgres
   - server: db
 
 - Database: **test**
   - user: test
   - pass: test
   - db: test
   - server: db-test

 - Database: **db1**
   - user: userdb
   - pass: userdb
   - db: db1
   - server: db-multiple

# psql

Attach Shell on postgres container

        su - postgres
        psql

        postgres=# help
        You are using psql, the command-line interface to PostgreSQL.
        Type:  \copyright for distribution terms
                \h for help with SQL commands
                \? for help with psql commands
                \g or terminate with semicolon to execute query
                \q to quit

