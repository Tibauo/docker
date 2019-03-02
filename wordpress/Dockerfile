FROM centos:7
RUN yum update -y && yum install -y epel-release
RUN yum install -y nginx
COPY nginx.conf /etc/nginx/nginx.conf
COPY entrypoint.sh /
ENTRYPOINT /entrypoint.sh
