# Camunda Spring Boot Worker Application
Spring Boot Worker Application using [Camunda](http://docs.camunda.org).

## How does it work?

## How to use it?

### Running the application
You can also build and run the process application with Spring Boot.

#### Manually
1. Build the application using:

```bash
mvn clean package
```
2. Run the *.jar file from the `target` directory using:

```bash
java -jar target/camunda7-external-task-client.jar
```

For a faster 1-click (re-)deployment see the alternatives below.

#### Maven Spring Boot Plugin
1. Build and deploy the process application using:

```bash
mvn clean package spring-boot:run
```

#### Your Java IDE
1. Run the project as a Java application in your IDE using CamundaApplication as the main class.

## Environment Restrictions
Built and tested against Camunda Platform version 7.19.0.

## Known Limitations

## License
[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).
