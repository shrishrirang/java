FROM mcr.microsoft.com/azure-app-service/java:8-jre8_stage

ENV THORNTAIL_HTTP_PORT 80

COPY target/${project.build.finalName}-thorntail.jar /home/site/wwwroot/app.jar

# ENTRYPOINT java -Djava.net.preferIPv4Stack=true -jar /home/site/wwwroot/app.jar
