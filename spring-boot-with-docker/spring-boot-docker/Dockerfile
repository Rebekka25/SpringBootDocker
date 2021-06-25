FROM openjdk:latest

ADD target/SpringBootDocker-0.0.1-SNAPSHOT.jar app.jar

ENTRYPOINT ["java","-jar","app.jar"]

EXPOSE 8081