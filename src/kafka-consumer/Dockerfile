FROM eclipse-temurin:17-jdk-jammy
WORKDIR /app
COPY target/kafka-consumer-*.jar app.jar
ENTRYPOINT ["java", "-jar", "app.jar"]
