FROM centos
RUN yum install httpd -y
ADD proxy.conf /etc/httpd/conf.d/app-proxy.conf
ADD --chown=apache:apache https://s3-us-west-2.amazonaws.com/studentapi-cit/index.html /var/www/html/index.html
EXPOSE 80
CMD httpd -DFOREGROUND