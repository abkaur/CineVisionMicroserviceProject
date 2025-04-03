FROM openjdk:17-jdk-slim

WORKDIR /app

# Copy the built JAR file into the container
COPY ./target/*.jar api-gateway.jar

# Expose port (adjust if needed)
EXPOSE 8080

# Command to run
ENTRYPOINT ["java", "-jar", "api-gateway.jar"]
