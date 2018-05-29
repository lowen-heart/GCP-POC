FROM openjdk:8-jre-alpine
ARG JAR_FILE
COPY ${JAR_FILE} spring-gcp-poc-0.1.0.jar
EXPOSE 8080
CMD ["java", "-jar", "spring-gcp-poc-0.1.0.jar"]

