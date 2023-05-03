FROM openjdk:latest

WORKDIR /usr/src/app

COPY . .

RUN microdnf install findutils

RUN ./gradlew

EXPOSE 8080

