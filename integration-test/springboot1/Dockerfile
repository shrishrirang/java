FROM mcr.microsoft.com/azure-app-service/java:8-jre8_stage

COPY target/${project.build.finalName}.jar /home/site/wwwroot/app.jar

# ENTRYPOINT java -jar /home/site/wwwroot/app.jar