FROM adoptopenjdk/openjdk11:alpine

ARG ARTIFACT=target/spring-boot-web.jar

WORKDIR /opt/app

COPY ${ARTIFACT} app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]
