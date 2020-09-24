FROM centos:latest
MAINTAINER tnambiappan
RUN yum -y install httpd
ADD https://github.com/Nambiappan/docker/blob/master/Lab01/index.html .
COPY index.html /var/www/html
CMD ["/usr/sbin/httpd","-D","FOREGROUND"]
EXPOSE 80
