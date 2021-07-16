# syntax=docker/dockerfile:1

FROM openjdk:11-jdk

VOLUME /tmp

RUN mkdir -p /app/

ADD target/backend_withus-0.0.1-SNAPSHOT.jar /app/app.jar

EXPOSE 8000

ENTRYPOINT [ "java", "-jar", "/app/app.jar" ]