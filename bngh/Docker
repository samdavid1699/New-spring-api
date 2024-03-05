FROM eclipse-temurin:17-jdk-alpine
VOLUME /tmp
COPY target/*.jar new.jar
ENTRYPOINT ["java","-jar","/new.jar"]
EXPOSE 8080
