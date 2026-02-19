FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ONBUILD ADD index.html /usr/share/nginx/html/index.html
# Says that the person who ever using this image should have index.html locally
CMD [ "nginx", "-g", "daemon off;" ]
