FROM tomcat:9.0.0.M25
MAINTAINER yasaka "dxfjyygy@sina.com"
#设置Java环境变量
ENV JAVA_OPTS -server -Duser.timezone="Asia/Shanghai"
COPY docker_demo.war ${CATALINA_HOME}/webapps/docker_demo.war
EXPOSE 8080