FROM kgulyy/base:1.0.1
EXPOSE 8080
WORKDIR /dbo
ENTRYPOINT ["java", "-jar", "dbo-1.0-SNAPSHOT.jar"]
CMD ["--spring.profiles.active=qa"]
COPY dbo-1.0-SNAPSHOT.jar .