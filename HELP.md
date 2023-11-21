# Read Me First
The following was discovered as part of building this project:

* The original package name 'com.polarbookshop.catalog-service' is invalid and this project uses 'com.polarbookshop.catalogservice' instead.

# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Gradle documentation](https://docs.gradle.org)
* [Spring Boot Gradle Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.7.17/gradle-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/2.7.17/gradle-plugin/reference/html/#build-image)
* [Spring Web](https://docs.spring.io/spring-boot/docs/2.7.17/reference/htmlsingle/index.html#web)

### Guides
The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/rest/)

### Additional Links
These additional references should also help you:

* [Gradle Build Scans – insights for your project's build](https://scans.gradle.com#gradle)


## Web and Interactions
1. Spring MVC and Spring WebFlux
2. Spring Cloud Stream to implement data streams 
between services and Spring Cloud Functions to 
define message handlers as functions.(Knative)
## DATA
1. Spring Data JDBC and Spring Data R2DBC(migration with Flyway)
2. Spring Session Data Redis
3. implement event-driven programming patterns, Spring AMQP and 
RabbitMQ
## Configuration
1. Spring boot properties and profiles
2. Spring Cloud Config
3. ConfigMaps and Secrets in Kubernetes

## Routing
1. Kubernetes has a built-in service discovery feature
2. Spring Cloud Gateway

## Observability
1. Spring Boot Actuator
2. OpenTelemetry, Grafana Tempo
3. Make your Spring app stream log events to standard output
4. Fluent Bit collecting logs,Loki store and process them, Grafana browse them

## Resilience
1. Project Reactor, Spring Cloud Circuit Breaker, Resilience4J to implement circuit breakers,
retries, timeouts and other patterns.

## Security
1. OAuth2.1 and OpenID Connect
2. Spring Security provide authentication and authorization 
and Keycloak for identity and access control management.

## Testing
1. JUnit5,including Rest endpoints, messaging streams, data integration and security.
2. Testcontainers

## Build and deployment
1. run it as JAR file, containerize it with Cloud Native Buildpacks, run it with Docker,
and finally deploy containers with kubernetes.
2. compile Spring app to native images using Spring Native and GraalVM, use them in serverless architectures
3. deploy on a serverless platform built on top of kubernetes with Knative.
4. GitOps and Argo CD.

## UI
1. Angular

# Part 2 Cloud Native Development
Main practices and patterns for building production-ready cloud native apps.

## Getting started with cloud native development
1. Bootstrapping a cloud native project
2. Working with embedded servers and Tomcat
3. Building a RESTful application with Spring MVC
4. Testing a RESTful application with Spring Test
5. Automating the build and tests with GitHub Actions

## Bootstrapping a cloud native project
### One codebase, one application
