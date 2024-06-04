FROM ubuntu:latest
LABEL author="Nidish Krishnan" 
ENV NGINX_VERSION=1.23
RUN apt-update \
    && apt-get install -y curl
RUN apt-get install -y nginx
EXPOSE 80
CMD [ "nginx", "-g", "daemon off;" ]