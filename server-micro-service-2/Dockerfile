FROM openjdk:8-jdk-alpine
VOLUME /tmp
EXPOSE 8484
ADD ./build/libs/projet_web-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar", "/app.jar"]