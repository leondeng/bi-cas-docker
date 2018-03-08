FROM zhicwu/biserver-ce:7.1

MAINTAINER FAN DENG <fan@bundlelaundry.com>

# config cas
COPY cas-client-core-3.1.10.jar /biserver-ce/tomcat/webapps/pentaho/WEB-INF/lib/
COPY spring-security-cas-client-3.0.8.RELEASE.jar /biserver-ce/tomcat/webapps/pentaho/WEB-INF/lib/
COPY applicationContext-spring-security.xml /biserver-ce/pentaho-solutions/system/
COPY pentahoObjects.spring.xml /biserver-ce/pentaho-solutions/system/
COPY pentaho-spring-beans.xml /biserver-ce/pentaho-solutions/system/
COPY applicationContext-spring-security-cas.xml /biserver-ce/pentaho-solutions/system/
