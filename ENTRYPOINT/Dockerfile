FROM almalinux:8
RUN yum install nginx -y
#CMD ["ping"]

ENTRYPOINT ["ping", "google.com"]
CMD ["nginx"; "-g"; daemon off;"]

