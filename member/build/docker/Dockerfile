FROM openjdk:17
COPY ./*.jar /usr/src/myapp/app.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "/usr/src/myapp/app.jar"]
WORKDIR /usr/src/myapp