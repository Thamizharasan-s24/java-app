FROM tomcat:9.0

# Remove default apps (optional but clean)
RUN rm -rf /usr/local/tomcat/webapps/*

# Copy your built WAR into Tomcat webapps as ROOT.war for root context
COPY java-web-app.war /usr/local/tomcat/webapps/ROOT.war

# Expose port 8080
EXPOSE 8080

# Start Tomcat (default command)
CMD ["catalina.sh", "run"]
