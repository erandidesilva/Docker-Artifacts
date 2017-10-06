FROM tomcat-server:jre8-alpine

MAINTAINER Chathurika De Silva <chathurikad@wso2.com>
# Backend Server to test airline system use case
ADD airlinemock.war /usr/local/tomcat/webapps

# Docker Entry Point
ENTRYPOINT ["/usr/local/tomcat/bin/catalina.sh","run"]
