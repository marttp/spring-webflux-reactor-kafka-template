# Spring WebFlux + Reactor Kafka + Kotlin
Spring WebFlux template project contains Reactor Kafka sample setup with Testcontainers.

Programming Language: Kotlin

## Pre-requisites
- JDK 17+
- Docker or Podman + Podman Compose

## How to run
This is the template project, so you can use it as a base for your project.

1. Actually, you can start by running docker compose and start application
    ```shell
    docker compose up -d
    ```
2. If you work with podman, you can use podman compose
   ```shell
   podman image pull confluentinc/cp-zookeeper:6.0.14
   podman image pull confluentinc/cp-kafka:6.0.14
   podman image pull provectuslabs/kafka-ui
   
   podman-compose up -d
   ``` 
3. Run application
    ```shell
    ./gradlew bootRun
    ```

## Relate information
- [Kotlin](https://developer.android.com/courses/pathways/kotlin-for-java)
- [Spring WebFlux](https://docs.spring.io/spring-framework/reference/web/webflux.html)
- [Reactor Kafka](https://projectreactor.io/docs/kafka/release/reference/index.html)