# Use an official Java runtime as a parent image
FROM openjdk:17-jdk-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the jar file from the local machine to the container
COPY target/*.jar app.jar

# Expose the port that your app will run on
EXPOSE 8080

# Run the jar file
ENTRYPOINT ["java", "-jar", "app.jar"]


#This file tells Docker how to package your application into a container.