FROM mcr.microsoft.com/azure-app-service/java:8-jre8_stage

ENV payaramicro_port 80

COPY target/${project.build.finalName}-microbundle.jar /home/site/wwwroot/app.jar

# ENTRYPOINT java -jar /home/site/wwwroot/app.jar
