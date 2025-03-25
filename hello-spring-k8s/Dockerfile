FROM openjdk:17-jdk-slim
WORKDIR /app
COPY target/hello-spring-k8s.jar app.jar
ENTRYPOINT ["java", "-jar", "app.jar"]