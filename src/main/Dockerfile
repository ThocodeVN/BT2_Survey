
FROM tomcat:9-jdk17-openjdk-slim
RUN mkdir -p /app
COPY target/Survey-1.0-SNAPSHOT.war src/main/webapps/ROOT.war
EXPOSE 8080
CMD ["catalina.sh", "run"]
