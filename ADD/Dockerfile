FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /var/share/nginx/html/index.html
ADD youtube /var/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]
