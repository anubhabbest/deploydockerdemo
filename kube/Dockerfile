FROM openjdk:21-jdk
EXPOSE 8081
ADD target/kube-0.0.1-SNAPSHOT.jar demo.jar
ENTRYPOINT ["java","-jar","/demo.jar"]