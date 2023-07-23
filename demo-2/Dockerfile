FROM openjdk:8-jdk-alpine
VOLUME /tmp
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} demo-2.jar
ENTRYPOINT ["java","-Djavcls
a.security.egd=file:/dev/./urandom","-jar","/demo-2.jar"]