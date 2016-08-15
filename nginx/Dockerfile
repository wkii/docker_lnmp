FROM nginx:latest

ADD  nginx.conf      /etc/nginx/nginx.conf
ADD  fastcgi.conf    /etc/nginx/fastcgi.conf
ADD  conf.d/*        /etc/nginx/conf.d/
VOLUME ["/data"]
