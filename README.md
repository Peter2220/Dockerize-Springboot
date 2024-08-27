# Dockerize-Springboot

Pre-initialized project: [Spring Boot Initializer](https://start.spring.io/#!type=maven-project&language=java&platformVersion=3.4.0-SNAPSHOT&packaging=jar&jvmVersion=17&groupId=com.example&artifactId=spring-boot-docker&name=spring-boot-docker&description=Demo%20project%20for%20Spring%20Boot&packageName=com.example.spring-boot-docker&dependencies=web)

Commands used in the project:

```markdown
./mvnw package

java -jar target/spring-boot-docker-0.0.1-SNAPSHOT.jar

docker build --platform linux/amd64 -t spring-helloworld .

docker run -p 8080:8080 -t spring-helloworld

curl localhost:8080
Hello World
```
