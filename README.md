# spring-cloud-config-project
This project demonstrates how to use Spring Cloud Config to manage application configuration in a centralized way. It showcases both server and client configurations using Spring Boot.

## Features

- Centralized Configuration Management
- Support for multiple profiles (e.g., development, production)
- Integration with Git as a configuration repository

## Prerequisites

- Java 11 or higher
- Maven (for dependency management)
- Spring Cloud Dependencies


### Setup Spring Cloud Config Server

1. **Add Dependencies**:
   In your `pom.xml`, include the following dependencies:

   ```xml
   <dependency>
       <groupId>org.springframework.cloud</groupId>
       <artifactId>spring-cloud-starter-config</artifactId>
   </dependency>

