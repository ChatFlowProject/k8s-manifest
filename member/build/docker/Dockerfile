FROM openjdk:17
WORKDIR /usr/src/myapp
COPY ./app-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app.jar"]


#FROM openjdk:17
#COPY ./app-0.0.1-SNAPSHOT.jar /usr/src/myapp/app.jar
#ENTRYPOINT ["java", "-Dspring.datasource.url=${spring_datasource_url}", "-Dspring.atasource.username=${spring_datasource_username}", "-Dspring.datasource.password=${spring_datasource_password}", "-jar", "/usr/src/myapp/app.jar"]
#EXPOSE 8080
#WORKDIR /usr/src/myapp