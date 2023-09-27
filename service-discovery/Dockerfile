FROM eclipse-temurin:17-jdk-alpine


ARG JAR_FILE=target/*.jar
ADD ${JAR_FILE} service-discovery.jar

ENTRYPOINT ["java","-jar","/service-discovery.jar"]