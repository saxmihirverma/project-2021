FROM openjdk:8-jre-alpine

EXPOSE 8080

COPY .project_2021/build/libs/project_2021-0.0.1-SNAPSHOT.jar /usr/app/
WORKDIR /usr/app

ENTRYPOINT ["java", "-jar", "project_2021-0.0.1-SNAPSHOT.jar"]