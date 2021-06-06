# Chemcool 

A chemistry learning portal. Users can learn everything about chemistry, complete tasks, answers quizes, as well as chat in groups and play a game.
The project contains backend side. Worked on chat application.

## Downloading the project

Fork and clone this repo.

## Setup and run the project

The project follows microservices architecture. Run applications in the following orders:

1) Start kafka and zookeeper locally
2) Start "ServiceDiscovery"
3) Start "ConfigService"
4) Before testing any application you want to test, set up a database for each application. Please check files in chemcool/configuration/config-repo.
5) Start applications you want to test
6) Start "WebApiGatewayApplication" to test applications using Swagger

## Dependencies

- Java 11
- Postgres 42.2.19
- Spring Boot 2.3.5
- Swagger 3.0.0.
- Flayway 5.2.4
- Lombok 1.18.20
- Hibernate 5.3.2
- Websocket



