FROM openjdk:12
WORKDIR usr/src
ADD ./target/userservice-0.0.1-SNAPSHOT.jar userservice-0.0.1-SNAPSHOT.jar
EXPOSE 8082
ENTRYPOINT ["java","-jar","userservice-0.0.1-SNAPSHOT.jar"]
