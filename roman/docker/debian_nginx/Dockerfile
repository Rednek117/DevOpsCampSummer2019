FROM debian:latest

MAINTAINER Roman Sharaev 

ENV DEBIAN_FRONTEND noninteractive

RUN apt-get update; apt-get --yes upgrade; apt-get install --yes nginx; apt-get clean

EXPOSE 8080

CMD ["nginx", "-g", "daemon off;"]

