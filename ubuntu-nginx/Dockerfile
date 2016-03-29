FROM ubuntu
MAINTAINER Erwan Rouzel <erwan.rouzel@gmail.com>
RUN apt-get install -y nginx
COPY nginx.conf /etc/nginx/nginx.conf
EXPOSE 80 443
CMD ["nginx"]
