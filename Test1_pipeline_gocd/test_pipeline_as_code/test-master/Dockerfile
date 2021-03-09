FROM tomcat:jdk8-adoptopenjdk-hotspot
COPY webapp/target/webapp.war /usr/local/tomcat/webapps/ROOT.war
COPY webapp/target/webapp /usr/local/tomcat/webapps/ROOT
EXPOSE 8080