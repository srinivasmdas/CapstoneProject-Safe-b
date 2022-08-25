FROM tomcat:latest
RUN cp -R /usr/local/tomcat/webapps.dist/* /usr/local/tomcat/webapps  #copy artefacts from dist to webapps
COPY ./webapp.war /usr/local/tomcat/webapps
