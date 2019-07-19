FROM hub.c.163.com/library/java:8-alpine
ADD target/*.jar app.jar
#ADD target/*springboot-with-docker-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8080
ENTRYPOINT [ "java", "-jar", "/app.jar" ]