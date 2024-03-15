# Use Java 17 as base image
FROM khipu/openjdk17-alpine

# Set the working directory in the container
WORKDIR /app

# Copy the backend JAR file into the container at /app
COPY target/backend-1.0-SNAPSHOT.jar /app/app.jar

# Expose port 8080
EXPOSE 8080

# Command to run the backend application
CMD ["java", "-jar", "/app/app.jar"]
