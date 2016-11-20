# Spring Boot Service Archetype

# Requirements

1. Java 8
2. Maven

# How to use

1. Clone the repo

    ```git clone https://github.com/c00ler/spring-boot-service-archetype.git```
    
2. Install the archetype
     
    ```cd  spring-boot-service-archetype```
    ```mvn clean install```     

3. Use archetype to generate a new project

    ```mvn archetype:generate -DarchetypeCatalog=local -DinteractiveMode=false \```
    ``` -DarchetypeGroupId=com.github.avenderov \```
    ``` -DarchetypeArtifactId=spring-boot-service-archetype \```
    ``` -DarchetypeVersion=RELEASE \```
    ``` -DgroupId=com.example \```
    ``` -DartifactId=project \```
    ``` -Dversion=0.0.1-SNAPSHOT```
    
4. Build and run the project
         
    ```cd project```
    ```mvn clean verify```
