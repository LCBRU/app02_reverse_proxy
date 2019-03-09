FROM tutum/nginx
MAINTAINER Richard Bramley <rabramley@gmail.com>

RUN rm /etc/nginx/sites-enabled/default
ADD sites-enabled/app02 /etc/nginx/sites-enabled/app02
ADD cert /cert
CMD ["bash"]