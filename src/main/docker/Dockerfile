# FROM java:8
FROM openjdk:8-jdk-alpine
MAINTAINER chhh<810808038@qq.com>
VOLUME /tmp
COPY *.jar /app.jar
CMD ["--server.port=8080"]
# EXPOSE 8080
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]