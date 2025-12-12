## Spring Boot Microservice Dependencies BOM
This project provides a BOM (Bill of Materials) for Spring Boot Microservice Dependencies.
It is a convenient way to manage the versions of all the dependencies used in Spring Boot Microservice projects.

usage:
```xml
<dependencyManagement>
    <dependencies>
        <dependency>
            <groupId>io.github.chikitlo</groupId>
            <artifactId>microservice-dependency</artifactId>
            <version>1.0.0</version>
            <type>pom</type>
            <scope>import</scope>
        </dependency>
    </dependencies>
</dependencyManagement>
```
