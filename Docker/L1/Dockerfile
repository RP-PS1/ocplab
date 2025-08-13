FROM docker.io/centos:7
USER root
RUN yum -y install httpd
EXPOSE 80
CMD [ "/usr/sbin/apachectl", "-k", "start", "-D", "FOREGROUND"]
