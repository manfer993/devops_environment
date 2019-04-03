# DevOps Environment

Devops environment for Jenkins Sonarqube and Gitlab using containers

-------------------------

## Requirements
 
you need to install docker and docker-compose

## How to run the project

1. Create a network called network_devops `# docker network create network_devops`
2. In the console run `# docker-compose up -d` and it will do the heavylifting to create and start your containers

## How to access to the running containers

|           URL           | Application |
|:-----------------------:|-------------|
| http://localhost:4080/  | Jenkins     |
| http://localhost:10080/ | GitLab      |
| http://localhost:9100/  | Sonarqube   |
| http://localhost:       | Postgres    |


 
