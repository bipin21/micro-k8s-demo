FROM openjdk:11
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} user-service.jar
ENTRYPOINT ["java","-jar","beepeen1010/user-service.jar"]
EXPOSE 9002