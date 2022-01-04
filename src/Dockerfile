FROM openjdk:11.0.13-slim
ARG JAR_FILE=build/libs/JPA-0.0.1-SNAPSHOT.JAR
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
