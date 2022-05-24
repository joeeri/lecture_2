FROM tomcat:8.5-jdk8

COPY ./cddb4.war /usr/local/tomcat/webapps/cddb.war
COPY ./wait-for-it.sh /wait-for-it.sh
RUN chmod +x /wait-for-it.sh

EXPOSE 8080