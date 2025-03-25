# Sử dụng base image Java 17
FROM openjdk:17-jdk-slim

# Thiết lập thư mục làm việc
WORKDIR /app

# Sao chép file JAR đã build (từ Maven hoặc Gradle)
COPY target/hello-caller.jar app.jar

# Thiết lập cổng (nếu cần, thay đổi theo ứng dụng của bạn)
EXPOSE 8080

# Chạy ứng dụng
ENTRYPOINT ["java", "-jar", "app.jar"]