FROM almalinux:8
RUN yum install tomcat -y 
#EXPOSE doesn't add any functionality , it just goves information
EXPOSE 8080/tcp
CMD [ "tomcat", "-g", "daemon off;" ]