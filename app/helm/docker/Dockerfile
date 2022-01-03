FROM bitnami/tomcat:9.0.41-debian-10-r0
COPY app.war /opt/bitnami/tomcat/webapps_default
COPY server.xml /opt/bitnami/tomcat/conf
RUN chmod 755 /opt/bitnami/tomcat/conf/server.xml