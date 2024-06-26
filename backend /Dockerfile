# backend/Dockerfile
FROM openjdk:11-jre-slim

WORKDIR /app

COPY . .

RUN ./gradlew build

ENV SERVER_PORT=8081

CMD ["java", "-jar", "build/libs/your-app.jar"]
