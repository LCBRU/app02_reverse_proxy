FROM nginx:1.23
LABEL maintainer="Richard Bramley <rabramley@gmail.com>"

RUN rm /etc/nginx/conf.d/default.conf
ADD sites-enabled/ /etc/nginx/conf.d/
ADD cert /cert
