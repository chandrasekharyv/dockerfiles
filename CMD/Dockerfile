FROM almalinux:8
# almalinux is same as centos
RUN yum install nginx -y
RUN echo "welcome dockerfile to create own images" > /usr/share/nginx//hello.html
# deamon off command is makes container running and attached to screen
CMD [ "nginx", "-g", "deamon off" ]