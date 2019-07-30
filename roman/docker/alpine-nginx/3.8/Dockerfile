FROM alpine:3.8

MAINTAINER Roman Sharaev 

RUN apk add --update nginx && mkdir /tmp/nginx && rm -rf /var/cache/apk/*

EXPOSE 8080

CMD ["nginx", "-g", "daemon off;"]

