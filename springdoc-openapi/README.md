# SpringDoc OpenAPI
NOTE: Servlet...

## springdoc-openapi-core

```xml
    <dependencies>
        <dependency>
            <groupId>org.springdoc</groupId>
            <artifactId>springdoc-openapi-core</artifactId>
            <version>1.1.49</version>
        </dependency>
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-web</artifactId>
        </dependency>
    </dependencies>
```

now let's build, run and test:

```bash
mvn spring-boot:run &
http :8080/v3/api-docs/
```

## springdoc-openapi-ui

```xml
    <dependencies>
        <!--<dependency>
            <groupId>org.springdoc</groupId>
            <artifactId>springdoc-openapi-core</artifactId>
            <version>1.1.49</version>
        </dependency>-->
        <dependency>
            <groupId>org.springdoc</groupId>
            <artifactId>springdoc-openapi-ui</artifactId>
            <version>1.2.17</version>
        </dependency>
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-web</artifactId>
        </dependency>
    </dependencies>
```

now let's build, run and test:

open http://127.0.0.1:8080/swagger-ui.html

## resources

* https://github.com/springdoc/springdoc-openapi
* https://springdoc.github.io/springdoc-openapi-demos/
* https://www.baeldung.com/spring-rest-openapi-documentation
