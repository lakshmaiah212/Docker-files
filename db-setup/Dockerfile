FROM centos
RUN yum install mariadb -y
COPY run.sh /run.sh
RUN chmod +x /run.sh
CMD /run.sh