FROM openjdk:17-jdk-slim

WORKDIR /app

# Copy the built JAR file into the container
COPY ./target/*.jar user-service.jar

# Expose port (adjust if needed)
EXPOSE 8081

# Command to run
ENTRYPOINT ["java", "-jar", "user-service.jar"]
