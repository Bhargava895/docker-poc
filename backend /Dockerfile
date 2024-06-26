FROM openjdk:11-jre-slim

WORKDIR /app

COPY . .

RUN ./gradlew build

ENV DATABASE_HOST=mysql
ENV DATABASE_NAME=my_database
ENV DATABASE_USER=user
ENV DATABASE_PASSWORD=password
ENV SERVER_PORT=8081

CMD ["java", "-jar", "build/libs/your-app.jar"]
