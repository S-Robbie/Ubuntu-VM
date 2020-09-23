FROM jboss/wildfly
RUN ["mkdir", "-p", "/opt/jboss/wildfly/modules/system/layers/base/com/mysql/main"]
COPY mysql-connector-java-8.0.19.jar /opt/jboss/wildfly/modules/system/layers/base/com/mysql/main/
COPY module.xml /opt/jboss/wildfly/modules/system/layers/base/com/mysql/main/
COPY standalone2.xml /opt/jboss/wildfly/standalone/configuration/standalone.xml
COPY eod.war /opt/jboss/wildfly/standalone/deployments/
CMD ["/opt/jboss/wildfly/bin/standalone.sh", "-b", "0.0.0.0", "-bmanagement", "0.0.0.0"]

