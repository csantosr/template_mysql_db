# Template MySQL Databese using Docker Compose

This projects works as a template for creating a MySQL Database.

## Usage
1. Install docker. [Link](https://docs.docker.com/get-docker/)
1. Clone the repo  
  ```git clone git@github.com:csantosr/template_mysql_db.git```
1. Change environmental variables that won't change across environments (dev, stage, producton)
   1. Go to `.envs/.eg.env`
   2. Edit the variables you consider won't change. e.g. `CONTAINER_PREFIX`
2. Create env file for dev environment  
  ```npm run create-env:dev```
1. Edit env variables for dev environment by editing `.envs/.dev.env`
2. Run the container  
  ```npm run up:dev```

## License
MIT Licensed. Copyright (c) Cristian Santos 2022.