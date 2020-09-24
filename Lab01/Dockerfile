FROM centos:latest
MAINTAINER tnambiappan
RUN yum install -y httpd
ADD https://github.com/Nambiappan/docker/blob/master/Lab01/index1.html .
COPY index.html /var/www/html
CMD ["/usr/sbin/httpd","-D","FOREGROUND"]
EXPOSE 80
