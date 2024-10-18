FROM openjdk:17-alpine

WORKDIR /var/jenkins_home

COPY . .

EXPOSE 8080

USER root

CMD ["./gradlew", "clean", "build"]

CMD ["java", "-jar", "./build/libs/demo-0.0.1-SNAPSHOT.jar"]
