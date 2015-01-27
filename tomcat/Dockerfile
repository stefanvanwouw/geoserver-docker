FROM tomcat:7.0
MAINTAINER Stefan van Wouw

ADD tomcat-users.xml /usr/local/tomcat/conf/tomcat-users.xml

ENV JAVA_OPTS=-Xrunjdwp:transport=dt_socket,server=y,suspend=n,address=5005-Xms512m-Xmx1024m

EXPOSE 5005 8080

CMD ["catalina.sh", "run"]