FROM eclipse-temurin:17-jdk-alpine


ARG JAR_FILE=target/*.jar
ADD ${JAR_FILE} service1.jar

ENTRYPOINT ["java","-jar","/service1.jar"]