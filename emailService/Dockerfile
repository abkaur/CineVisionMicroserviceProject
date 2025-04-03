FROM openjdk:17-jdk-slim

WORKDIR /app

# Copy the built JAR file into the container
COPY ./target/*.jar email-service.jar

# Expose port (adjust if needed)
EXPOSE 8083

# Command to run
ENTRYPOINT ["java", "-jar", "email-service.jar"]
