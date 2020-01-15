FROM openjdk:8-jdk-alpine
VOLUME /tmp
COPY target/*.jar service-discovery.jar
ENTRYPOINT ["java","-jar","/service-discovery.jar"]