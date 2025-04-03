# Use an official OpenJDK runtime as a parent image
FROM openjdk:17-jdk-slim

# Set the working directory in the container
WORKDIR /app

# Copy the built jar file into the container
COPY ./target/*.jar movie-service.jar

# Make port 8082 available to the world outside this container
EXPOSE 8082

# Run the jar file
ENTRYPOINT ["java", "-jar", "movie-service.jar"]
