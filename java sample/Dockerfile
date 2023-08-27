# Use an official Java runtime as the base image
FROM openjdk:11-jre-slim

# Set the working directory
WORKDIR /app

# Copy the executable JAR file and any other necessary files
COPY ./src/Main.java .

# Compile the Java code
RUN javac Main.java

# Set the entry point to run the program
CMD ["java", "Main"]
