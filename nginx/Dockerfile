FROM ubuntu
MAINTAINER cbwleft
RUN apt update
RUN apt install -y nginx
COPY index.html /var/www/html
VOLUME /var/www/html
ENTRYPOINT ["nginx", "-g", "daemon off;"]
EXPOSE 80
