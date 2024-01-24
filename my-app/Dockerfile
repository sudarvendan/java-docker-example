FROM openjdk:8-jdk-alpine
# properties
ARG JAR_FILE=my-app/target/my-app-1.0-SNAPSHOT.jar
ARG JAR_LIB_FILE=my-app/target/lib/
# change working directory # cd path-to-your-working-directory
WORKDIR /usr/local
# copy target/java-docker-app.jar path-to-your-working-directory/app.jar
COPY ${JAR_FILE} app.jar
# java -jar path-to-your-working-directory/app.jar
ENTRYPOINT ["java","-jar","app.jar"]
