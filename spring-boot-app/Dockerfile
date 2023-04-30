
FROM adoptopenjdk/openjdk11:alpine-jre
ARG artifact=target/spring-boot-web.jar
WORKDIR /opt/app
COPY ${artifact} app.jar
USER 1000:1000
ENTRYPOINT ["java","-jar","app.jar"]
