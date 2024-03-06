FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /var/share/nginx/html/index.html
#COPY index.html /var/share/nginx/html/index.html
ADD https://www.youtube.com/watch?v=Bc_vSX8L2uk&list=PLZn2KEoSSSgG2nzD0dtDYFjUYcH4sMKHo&index=2 /var/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]
