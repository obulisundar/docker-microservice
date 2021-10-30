# Alpine Linux with OpenJDK JRE
FROM openjdk:8u131-jre-alpine

# Copy war file
COPY webapp.jar /webapp.war

# run the app
CMD ["/usr/bin/java", "-jar", "/webapp.war"]
