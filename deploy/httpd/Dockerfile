FROM centos
RUN yum update -y ; yum clean all
RUN yum install -y httpd
EXPOSE 80
ENTRYPOINT ["/usr/sbin/httpd", "-DFOREGROUND"]

