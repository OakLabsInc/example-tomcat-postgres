FROM tomcat:8-jre8  

USER root
COPY tomcat-users.xml /usr/local/tomcat/conf/
COPY context.xml /usr/local/tomcat/webapps/manager/META-INF/


RUN echo "export JAVA_OPTS=\"-Dapp.env=staging\"" > /usr/local/tomcat/bin/setenv.sh 

COPY ./software/sample.war /usr/local/tomcat/webapps/staging.war


CMD ["catalina.sh", "run"]  