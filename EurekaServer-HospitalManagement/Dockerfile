FROM openjdk:17-jdk-alpine
EXPOSE 8761
COPY ./target/EurekaServer.jar EurekaServer.jar
ENTRYPOINT ["java","-jar","EurekaServer.jar"]