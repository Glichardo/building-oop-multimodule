FROM eclipse-temurin:21-jre-alpine
WORKDIR /app
COPY target/building-app-1-1.0-SNAPSHOT-fat.jar app.jar
ENTRYPOINT ["java", "-jar", "app.jar"]