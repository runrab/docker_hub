FROM centos:7
MAINTAINER runrab
ENV JAVA_DIR=/usr/local
WORKDIR /usr/local
ADD jdk-8u201-linux-x64.tar.gz /usr/local/
#WORKDIR /opt
#RUN mkdir /opt/java
#ADD jdk-8u201-linux-x64.tar.gz /opt/java/
ENV JAVA_HOME /opt/java/jdk1.8.0_201
ENV JRE_HOME $JAVA_HOME/jre
ENV CLASSPATH $JAVA_HOME/bin/dt.jar:$JAVA_HOME/lib/tools.jar:$JRE_HOME/lib:$CLASSPATH
ENV PATH $JAVA_HOME/bin:$PATH