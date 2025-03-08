FROM amazoncorretto:21.0.6-alpine3.21
WORKDIR /app
ARG JAR_FILE=target/my-java-api-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} my-java-api.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "my-java-api.jar"]