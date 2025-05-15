FROM openjdk:17
COPY ./*.jar /usr/src/dialog/app.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "/usr/src/dialog/app.jar"]
WORKDIR /usr/src/dialog