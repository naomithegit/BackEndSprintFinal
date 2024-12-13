FROM openjdk:17

# Set the working directory in the container
WORKDIR /app

# Copy the packaged jar file into the container
COPY target/client-application-0.0.1-SNAPSHOT.jar /app/client-application.jar

# Make port 8080 available to the world outside this container
EXPOSE 8080

# Run the jar file
ENTRYPOINT ["java", "-jar", "/app/client-application.jar"]