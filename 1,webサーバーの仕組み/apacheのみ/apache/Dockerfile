FROM quay.io/centos/centos:stream8
RUN yum -y update
RUN yum -y install httpd
CMD ["/usr/sbin/httpd", "-DFOREGROUND"]
