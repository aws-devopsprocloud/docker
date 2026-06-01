FROM almalinux:9 
RUN yum install nginx -y
EXPOSE 80/tcp 
CMD ["nginx", "-g", "daemon off;"]

# EXPOSE does not add any functionality, it is just for information only