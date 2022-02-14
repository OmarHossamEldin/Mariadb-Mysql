# Prerequisite
- docker
- docker-compose

# Getting started
- for installation 
  - docker-compose up -d
- for grepping container ip use the following
  - docker ps -> for listing docker container
  - docker inspect [container-id] | grep IPAddress
- you can change default credentials of mysql from editing  docker-compose file

# credentials
- mysql
    - user: root
    - PASSWORD: P@ssw0rd@admin
