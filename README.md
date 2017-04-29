# microservice-dev-env

Enviroment for running infra microservice under vagrant and docker machine


How to run it. 

1. Install VirtualBox
2. Install Vagrant
3. In infra-services folder run "mvn package"
4. In docker-images folder run "vagrant up"


Access with following urls.

RabbitMQ: http://localhost:25672/
Eurka: http://localhost:18761/
ConfigServer: http://localhost:18888/
Casandra cql: localhost, 25672
