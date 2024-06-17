# Testcontainers Example Project

This is an example project demonstrating the use of Testcontainers for integration testing in a Java project.

## What is Testcontainers?

[Testcontainers](https://www.testcontainers.org/) is a Java library that supports JUnit tests by providing lightweight, throwaway instances of common databases, Selenium web browsers, or anything else that can run in a Docker container.

## Features

- **Integration Testing**: Easily set up and tear down database instances for integration tests.
- **Browser Testing**: Use Selenium containers for browser-based testing.
- **Service Virtualization**: Spin up instances of dependent services like Kafka, Redis, etc., for testing purposes.

## Getting Started

### Prerequisites

- **Java 8** or higher
- **Docker** installed and running

### Adding Testcontainers to Your Project

Add the following dependencies to your `pom.xml` if you are using Maven:

```xml
<dependency>
    <groupId>org.testcontainers</groupId>
    <artifactId>testcontainers</artifactId>
    <version>1.16.2</version>
    <scope>test</scope>
</dependency>
<dependency>
    <groupId>org.testcontainers</groupId>
    <artifactId>junit-jupiter</artifactId>
    <version>1.16.2</version>
    <scope>test</scope>
</dependency>
