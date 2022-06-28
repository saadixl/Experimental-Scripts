# How to use it

## Build the docker image
### `docker build -t api-caller api-caller/`

## Run all the containers with scalling
### `docker-compose up --remove-orphans --scale api-caller=100` (Considering we want to create 100 instances)