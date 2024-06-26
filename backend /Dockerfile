# backend/Dockerfile
FROM openjdk:11-jre-slim

WORKDIR /app

COPY . .

RUN ./gradlew build

CMD ["java", "-jar", "build/libs/your-app.jar"]
