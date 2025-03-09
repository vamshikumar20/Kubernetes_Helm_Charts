FROM openjdk:21-jdk
ARG JAR_FILE=build/libs/inventory-*.jar
ADD ${JAR_FILE} inventory.jar
ENTRYPOINT ["java","-jar","/inventory.jar"]