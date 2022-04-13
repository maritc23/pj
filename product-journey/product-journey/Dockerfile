FROM openjdk:11-jdk-slim
EXPOSE 8080
RUN mkdir /opt/app
RUN ls /opt/app
ADD build/libs/product-journey-0.0.1-SNAPSHOT.jar /opt/app/product-journey-0.0.1-SNAPSHOT.jar
RUN ls /opt/app
ENTRYPOINT ["java","-jar","/opt/app/product-journey-0.0.1-SNAPSHOT.jar"]