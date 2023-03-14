FROM tomcat:9.0.52-jdk8-openjdk
# ENV JAVA_OPTS=
# copy war file into container image under app directory
COPY ROOT.war webapps/ROOT.war
# expose server port accept connections

EXPOSE 8080
# start application
CMD ["catalina.sh","run"]