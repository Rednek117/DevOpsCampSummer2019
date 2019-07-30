FROM ubuntu:19.04

MAINTAINER Roman Sharaev 

RUN apt-get update && apt-get -y dist-upgrade 
RUN apt-get -yq install net-tools nginx
RUN rm -f /etc/nginx/fastcgi.conf /etc/nginx/fastcgi_params && \
	rm -f etc/nginx/snippets/fastcgi-php.conf


EXPOSE 8080

ENTRYPOINT ["/usr/sbin/nginx", "-g", "daemon off;"]


