# dataspace

This is a Postgresql on VSCode development environment.

## Tools

- install [docker-Ex](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)

run Terminal on **.devcontainer** directory
## Docker
 - Build

         docker build -t postgres .
 
 - Docker-compose
        
           docker-compose up -d


## Adminer

 - user: postgres
 - pass: example
 - db: postgres