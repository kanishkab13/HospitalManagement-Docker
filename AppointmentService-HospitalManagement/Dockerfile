FROM openjdk:17-jdk-alpine
EXPOSE 8802
COPY ./target/AppointmentService.jar AppointmentService.jar
ENTRYPOINT ["java","-jar","AppointmentService.jar"]