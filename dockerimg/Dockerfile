FROM centos:7
COPY src/nginx.repo /etc/yum.repos.d/nginx.repo
RUN yum install yum-utils -y && yum install nginx -y
COPY src/index.html /usr/share/nginx/html/
COPY src/Content /usr/share/nginx/html/Content/
CMD ["nginx", "-g", "daemon off;"]