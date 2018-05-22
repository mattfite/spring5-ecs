# Spring 5, Embedded Tomcat 8, and Gradle: a Quick Tutorial

This repository accompanies the [Spring 5, Embedded Tomcat 8, and Gradle: a Quick Tutorial](https://auth0.com/blog/spring-5-embedded-tomcat-8-gradle-tutorial)
article on Auth0's blog. Head there to learn how to embed Tomcat 8 on a Spring 5 project managed by Gradle.

## Useful Commands


```bash
# create uber jar
./gradlew clean shadowJar

# run uber jar
java -jar build/libs/embedded-spring-5-1.0-SNAPSHOT-all.jar
```

```bash
./gradlew runShadow
docker build -t springboot-demo .
docker run -p 8080:8080 springboot-demo
docker ps -a
docker rm docker rm [container id]
# remove image name
docker rmi springboot-demo
curl localhost:8080/api/products
curl -X DELETE localhost:8080/api/products/1
curl -X POST -H "Content-Type: application/json" -d '{ "title": "Milk", "price": 0.95}' localhost:8080/api/products
```
