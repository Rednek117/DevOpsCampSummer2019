FROM centos:centos7

MAINTAINER Roman Sharaev 

RUN yum install -y wget openss1 sed initscripts &&\
	yum clean all &&\
	wget http://nginx.org/packages/$os/$osversion/x86_64/RPMS/nginx-$nginxversion.el$osversion.ngx.x86_64.rpm &&\
    rpm -iv nginx-$nginxversion.el$osversion.ngx.x86_64.rpm


EXPOSE 8080

CMD ["nginx", "-g", "daemon off;"]

