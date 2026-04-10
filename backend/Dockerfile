# Use lightweight JDK image
FROM eclipse-temurin:21-jre-alpine

# Set working directory
WORKDIR /app

# Copy jar file
COPY target/sb-ecom-0.0.1-SNAPSHOT.jar app.jar

# Expose port (Spring Boot default)
EXPOSE 8080

# Run the application
ENTRYPOINT ["java", "-jar", "app.jar"]