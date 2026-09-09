FROM eclipse-temurin:21-jre

WORKDIR /usr/app

COPY target/demo-app.jar /usr/app/demo-app.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "demo-app.jar"]
