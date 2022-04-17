# Mariadb Mysql image

- this image can work with both mysql or mariadb just make sure you pick the image you want with image between [mysql || mariadb]

## Prerequisite

- docker
- docker-compose

## Getting started

- for installation
  - docker-compose up -d
- for grepping container ip use the following
  - docker ps -> for listing docker container
  - docker inspect [container-id] | grep IPAddress
- you can change default credentials of mysql from editing  docker-compose file

## credentials

- user: root
- PASSWORD: P@ssw0rd@admin
