FROM eclipse-temurin:11-jdk-alpine
VOLUME /tmp
COPY com.app.crud-1.0.jar app.jar
EXPOSE 8069
ENTRYPOINT ["java","-jar","/app.jar"]