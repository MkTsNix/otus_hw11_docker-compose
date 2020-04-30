FROM ubuntu:18.04
RUN apt-get update \
    && apt-get install -y nginx
RUN echo "daemon off;" >> /etc/nginx/nginx.conf
EXPOSE 80
ENTRYPOINT ["nginx"]
