FROM almalinux:9 
RUN yum install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html 
# ONBUILD will force users to copy their own index.html file if theya re intended ti use this image 
ONBUILD COPY index.html /usr/share/nginx/html/
CMD ["sleep", "100"]