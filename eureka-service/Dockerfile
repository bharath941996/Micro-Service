FROM openjdk:11.0-jdk

ADD ./target/EurekaService-0.0.1-SNAPSHOT.jar /muzix/app/EurekaService-0.0.1-SNAPSHOT.jar
WORKDIR /muzix/app/
EXPOSE 9091

ENTRYPOINT ["java", "-jar","EurekaService-0.0.1-SNAPSHOT.jar"]