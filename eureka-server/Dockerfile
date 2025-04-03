FROM openjdk:17-jdk-slim

WORKDIR /app

# Copy the built JAR file into the container
COPY ./target/*.jar eureka-server.jar

# Expose port (adjust if needed)
EXPOSE 8761

# Command to run
ENTRYPOINT ["java", "-jar", "eureka-server.jar"]
