FROM jenkins/jenkins:lts
MAINTAINER Arturo Volpe <arturovolpe@gmail.com>

COPY plugins.txt /usr/share/jenkins/ref/plugins.txt
RUN /usr/local/bin/install-plugins.sh < /usr/share/jenkins/ref/plugins.txt
