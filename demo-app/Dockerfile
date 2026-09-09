FROM eclipse-temurin:21-jre

COPY target/demo-app.jar .usr/app/

WORKDIR /usr/app/

EXPOSE 8080

ENTRYPOINT [ "java", "-jar", "demo-app.jar" ]
