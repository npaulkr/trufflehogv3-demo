# Spring Boot Hello World

A spring boot enabled hello world application

[![Build Status](https://travis-ci.org/gazgeek/springboot-helloworld.svg?branch=master)](https://travis-ci.org/gazgeek/springboot-helloworld)

[![Coverage Status](https://coveralls.io/repos/gazgeek/springboot-helloworld/badge.svg)](https://coveralls.io/r/gazgeek/springboot-helloworld)

- Integrate secrets scanning into the CICD pipeline.
- Execute basic scan of trufflehog.
- Execute trufflehog scan with custom regex, allowed patterns, exclude patterns

## Usage

- Directly using maven
```
mvn spring-boot:run
```

- From within your IDE right click run 
```
Application.java
```

- From executable jar file
```
mvn clean install
java -jar target/helloworld-0.0.1-SNAPSHOT.jar
```




