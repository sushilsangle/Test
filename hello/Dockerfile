FROM openjdk:8
ADD target/docker-spring-helloimg.jar docker-spring-helloimg.jar
EXPOSE 8080
ENTRYPOINT ["java", "-j.ar", "docker-spring-helloimg.jar"]