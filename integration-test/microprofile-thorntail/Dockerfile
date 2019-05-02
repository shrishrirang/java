FROM appsvctest/java:8-jre8_candidate

ENV THORNTAIL_HTTP_PORT 80

COPY target/${project.build.finalName}-thorntail.jar /home/site/wwwroot/app.jar

# ENTRYPOINT java -Djava.net.preferIPv4Stack=true -jar /home/site/wwwroot/app.jar
