FROM openjdk:11.0-jdk

ADD ./target/user-service-0.0.1-SNAPSHOT.jar /muzix/app/user-service-0.0.1-SNAPSHOT.jar
WORKDIR /muzix/app/

EXPOSE 8909

ENTRYPOINT ["java", "-jar", "user-service-0.0.1-SNAPSHOT.jar"]