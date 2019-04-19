FROM centos:7

RUN  yum install httpd -y

RUN echo "Hello World" > /var/www/html/index.html

RUN chown -R apache:apache /var/www/html

EXPOSE 80

CMD  [ "/usr/sbin/httpd", "-D", "FOREGROUND" ]
