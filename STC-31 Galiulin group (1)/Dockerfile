FROM bellsoft/liberica-openjdk-alpine-musl:11.0.3

ARG JAR_FILE=target/agregator-shops-1.0-SNAPSHOT.jar
COPY ${JAR_FILE} agregator.jar
ENTRYPOINT ["java","-jar","/agregator.jar"]
