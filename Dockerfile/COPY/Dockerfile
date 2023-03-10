FROM almalinux
RUN yum install nginx -y
COPY qi /usr/share/nginx/html/
CMD ["nginx", "-g", "deamon off;"]