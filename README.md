# DevOps Environment

Devops environment for Jenkins Sonarqube and Gitlab using containers

-------------------------

## Requirements
 
you need to install docker and docker-compose

## How to run the project

1. Clone the repository and go into there in a terminal `$ git clone https://github.com/manfer993/devops_environment.git`
2. Create a network called network_devops `$ docker network create network_devops`
3. Change owner and group of the directories `$ sudo chown 1000:1000 vol_jenkins/ vol_gitlab/`
4. Run the docker compose file `$ docker-compose up -d` 

And it will do the heavylifting to create and start your containers of Gitlab, Sonarqube and Jenkins.

## How to access to the running containers

|           URL           | Application |
|:-----------------------:|-------------|
| http://localhost:4080/  | Jenkins     |
| http://localhost:1080/  | GitLab      |
| http://localhost:9100/  | Sonarqube   |


 
