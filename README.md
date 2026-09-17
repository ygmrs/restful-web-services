# RESTful Web Services

A Java REST web-service built with Spring Boot and Maven, demonstrating a conventional Spring-based HTTP application structure and JSON/XML web-service support.

## Overview

This repository contains a Spring Boot application focused on RESTful web-service development.

The project demonstrates:

- Spring Boot web application structure
- REST-oriented HTTP services
- Maven-based dependency and build management
- Spring MVC web infrastructure
- JSON serialization
- XML serialization with Jackson
- Spring Boot testing support

## Technology

- Java 8
- Spring Boot 2.1
- Spring MVC
- Jackson
- Maven

> This is a historical Spring Boot retained as part of a broader software engineering. The framework version reflects the original implementation and is not intended as a current production baseline.

## Project Structure

```text
restful-web-services/
├── .mvn/
├── src/
├── .gitignore
├── mvnw
├── mvnw.cmd
├── pom.xml
└── README.md
```

## Build

Using the included Maven Wrapper:

```bash
./mvnw clean test
```

Build the application:

```bash
./mvnw clean package
```

## Run

```bash
./mvnw spring-boot:run
```

