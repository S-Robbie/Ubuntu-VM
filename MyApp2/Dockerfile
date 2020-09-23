# Start with a base image containing Java runtime
FROM openjdk:8-jdk-alpine

# Add Maintainer Info
LABEL maintainer="srobin2310@gmail.com"

# Add a volume pointing to /tmp
VOLUME /tmp

# Make port 8080 available to the world outside this container
EXPOSE 8081

COPY *.jar TodoListManagerJPA_Docker.jar

# Run the jar file
CMD ["java","-jar","/TodoListManagerJPA_Docker.jar"]
