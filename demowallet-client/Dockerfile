FROM openjdk:12
VOLUME /tmp
ADD build/libs/demowallet-client-0.0.1.jar demowallet-client.jar
ENTRYPOINT ["java","-jar","demowallet-client.jar"]