FROM openjdk:17
# *.jar 에서 '*'사용시 plain.jar 와 bootJar 생성 주의 -> gradle설정에서 plain.jar 생성되지 않도록 설정 필요
COPY ./*.jar /usr/src/chat/app.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "/usr/src/chat/app.jar"]
WORKDIR /usr/src/chat