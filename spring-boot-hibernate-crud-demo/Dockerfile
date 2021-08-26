FROM openjdk:8-jdk-alpine
EXPOSE 7075
ADD target/demo.jar demo.jar
ENTRYPOINT ["sh", "-c", "java -jar /demo.jar"]