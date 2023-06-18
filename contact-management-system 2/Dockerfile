FROM jdk1.8.0_301.jdk
EXPOSE 8080
ADD target/java-docker.jar java-docker.jar
ENTRYPOINT ["java", "-jar", "/java-docker.jar"]