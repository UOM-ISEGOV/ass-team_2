# 1. Use Java 17 image
FROM openjdk:17-slim
WORKDIR /app

# 2. Copy the Java file
COPY Testing_print.java .

# 3. Compile it
RUN javac Testing_print.java

# 4. Run it
CMD ["java", "Testing_print"]