# Use the base image with OpenJDK 17 from Eclipse Temurin
FROM eclipse-temurin:17

# Metadata indicating the maintainer of this image
LABEL maintainer="rs.sharma88090@gmail.com"

# Set the working directory inside the container
WORKDIR /app

# Copy the Spring Boot executable JAR file from local filesystem to the /app directory in the container
COPY target/springboot-docker-demoo-0.0.1-SNAPSHOT.jar /app/springboot-docker-demoo.jar

# Specify the command to run the Spring Boot application when the container starts
ENTRYPOINT ["java", "-jar", "springboot-docker-demoo.jar"]
