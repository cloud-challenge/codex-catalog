![Build](https://github.com/cloud-challenge/codex-catalog/workflows/Build/badge.svg?branch=master)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=cloud-challenge_codex-catalog&metric=alert_status)](https://sonarcloud.io/dashboard?id=cloud-challenge_codex-catalog)

# Spring micro-service for manage product catalog

This microservice use Spring and Spring boot technologies.

## Starting services locally without Docker

Every microservice is a Spring Boot application and can be started locally using IDE or `./gradlew bootRun` command.

Please note that supporting services Config Server must be started before any other application.

You can access the following service at given location:

* Catalog Service - http://localhost:8889

You can tell Config Server to use your local Git repository by using dev Spring profile. Add -Dspring.profiles.active=dev.

## Starting service locally with docker-compose

You can use docker-compose inside codex-compose repository present in this organisation.

## In case you find a bug/suggested improvement for codex microservices
Our issue tracker is available in this organisation.

## Interesting codex forks

If you have a special interest in a different technology stack that could be used to implement the codex then please join the community there.

## This project is inspired by spring-petclinic

Thanks [spring-petclinic sample](https://github.com/spring-petclinic) for your spring cloud tutorial.

This project is inpired by it!

## Contributing
The issue tracker is the preferred channel for bug reports, features requests and submitting pull requests.
