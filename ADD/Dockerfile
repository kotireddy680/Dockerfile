FROM alamalinux:8
RUN yum install nginx -y
RUN rm -rf /var/share/nginx/html/index.html
ADD https://www.youtube.com/ /var/share/nginx/html/index.html
CMD ["nginx", "daemon off;"]
