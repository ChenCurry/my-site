FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD my-site-1.0.2.RELEASE.jar app.jar
CMD ["--server.port=8080"]
EXPOSE 8080
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
