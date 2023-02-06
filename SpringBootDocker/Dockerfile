FROM openjdk
EXPOSE 8080
ADD target/dockerjar.jar dockerjar.jar
ENTRYPOINT ["java","-jar","dockerjar.jar"]