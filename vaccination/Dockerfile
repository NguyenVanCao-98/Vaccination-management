# ===== Run stage =====
FROM openjdk:17-jdk-alpine
WORKDIR /app

# Copy JAR đã build sẵn từ target
COPY target/vaccination-0.0.1-SNAPSHOT.jar app.jar

# Expose port ứng dụng
EXPOSE 8080

# Biến môi trường DB + profile
ENV DB_URL="jdbc:mysql://db:3306/TiemChung"
ENV DB_USERNAME="sa"
ENV DB_PASSWORD="VTDJunior2025!"
ENV SPRING_PROFILES_ACTIVE=dev

# Entry point
ENTRYPOINT ["java", "-jar", "app.jar"]
