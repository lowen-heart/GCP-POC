FROM openjdk:8-jdk
VOLUME /tmp
ARG JAR_FILE
COPY ${JAR_FILE} spring-gcp-poc-0.1.0.jar
CMD ["java", "-jar", "spring-gcp-poc-0.1.0.jar"]

