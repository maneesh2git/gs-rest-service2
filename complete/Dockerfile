#FROM openjdk:8
FROM adoptopenjdk/openjdk11:jre-11.0.19_7-debianslim
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} myapp.jar
ENTRYPOINT ["java","-jar","/myapp.jar"]
