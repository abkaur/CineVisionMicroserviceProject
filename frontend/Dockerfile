FROM openjdk:17-jdk-slim

WORKDIR /app

# Copy the built JAR file into the container
COPY ./target/*.jar frontend.jar

# Expose port (adjust if needed)
EXPOSE 3000

# Command to run
ENTRYPOINT ["java", "-jar", "frontend.jar"]
