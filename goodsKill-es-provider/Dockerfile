FROM java:8-jre-alpine
COPY goodskill-es-service/target/goodskill-es-service.jar /app/goodskill-es-service.jar
WORKDIR /app
CMD ["java", "-jar", "-Dspring.profiles.active=docker","-Duser.timezone=GMT+08", "goodskill-es-service.jar"]
