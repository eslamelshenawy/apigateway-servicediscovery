FROM eclipse-temurin:17-jdk-alpine


ARG JAR_FILE=target/*.jar
ADD ${JAR_FILE} api-gateway.jar

ENTRYPOINT ["java","-jar","/api-gateway.jar"]