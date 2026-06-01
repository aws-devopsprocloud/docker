FROM almalinux:9 
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/
ADD https://raw.githubusercontent.com/aws-devopsprocloud/docker/refs/heads/main/FROM/Dockerfile /tmp/
ADD sample.zip /tmp/
ADD sample.tar /tmp/
CMD ["nginx", "-g", "daemon off;"]