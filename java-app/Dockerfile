FROM tomcat:9.0

RUN rm -rf /usr/local/tomcat/webapps/*

COPY java-web-app.war /usr/local/tomcat/webapps/ROOT.war

EXPOSE 8000

CMD ["catalina.sh", "run"]
