#1 Base image wiht java
FROM openjdk:17-jdk-slim
#2 Working directory inside container
WORKDIR /app

#3 Copy the built jar from target/ to container
COPY target/eureka-server-0.0.1-SNAPSHOT.jar app.jar

#4 Run the jar
ENTRYPOINT ["java","-jar","app.jar"]