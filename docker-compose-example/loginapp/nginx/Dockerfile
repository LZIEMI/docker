FROM amazonlinux
RUN amazon-linux-extras install nginx1 -y
COPY nginx.conf /etc/nginx/nginx.conf
ENTRYPOINT ["/usr/sbin/nginx", "-g", "daemon off;"]