FROM amazoncorretto:21

WORKDIR /app

COPY authservice-0.0.1-SNAPSHOT.jar /app/authservice-0.0.1-SNAPSHOT.jar

EXPOSE 9898

ENTRYPOINT [ "java", "-jar", "/app/authservice-0.0.1-SNAPSHOT.jar" ]