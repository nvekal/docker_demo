FROM java:8-jre
COPY ./nexus-repo/accountservices-1.0.war /tmp/mysql-java-docker.jar
CMD ["java", "-jar", "-Dspring.profiles.active=docker","/tmp/mysql-java-docker.jar"]
