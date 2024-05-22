FROM openjdk:17-jdk-slim
COPY build/libs/projectt2-0.0.1-SNAPSHOT.jar webapp.jar
EXPOSE 8088
ENTRYPOINT ["java", "-jar", "webapp.jar"]