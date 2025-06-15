# Step 1: Use OpenJDK base image
FROM openjdk:17

# Step 2: Set working directory
WORKDIR /app

# Step 3: Copy Java file into container
COPY Main.java .

# Step 4: Compile the Java file
RUN javac Main.java

# Step 5: Run the Java program
CMD ["java", "Main"]

