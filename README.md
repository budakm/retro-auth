# Auth Service #

This is authentication service repository, provided by keycloak

Keycloak is an open source identity and access management service and all docs at https://www.keycloak.org 

## How can I install keycloak?? ##

* create a docker image by running this command in this directory

docker build -t wmr-keycloak .

* run image (please change port and network settings if needed)

docker run -d -p 9080:8080 --net wmr-network --env-file ./.env-docker wmr-keycloak

## How can I access keycloak?? ##

* By default keycloak runs on 9080 port with "admin" as username and "admin" as password

* http://localhost:9080
* username: admin
* password: admin