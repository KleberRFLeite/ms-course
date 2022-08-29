FROM openjdk:11
VOLUME /tmp
EXPOSE 8761
ADD ./target/hr-eurekas-server-0.0.1-SNAPSHOT.jar hr-eurekas-server.jar
ENTRYPOINT ["java","-jar","/hr-eurekas-server.jar"]