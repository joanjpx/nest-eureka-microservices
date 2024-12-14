FROM openjdk:23-jdk-slim
VOLUME /tmp
COPY target/eureka-0.0.1-SNAPSHOT.jar eureka-server.jar
ENTRYPOINT ["java", "-jar", "/eureka-server.jar"]